<script lang="ts">

 import { toggleMode } from "mode-watcher";
 import { House ,BookMarked, Github,Linkedin,Sun,Moon} from '@lucide/svelte';


</script>
 
<main class="container mx-auto px-4 py-12">

<div class="flex">
  <div>
<div class="inline-block text-3xl font-bold tracking-tighter sm:text-5xl xl:text-6xl/none">
Hi, I&apos;m Kevin Solomon  
</div>
<div class="inline-block max-w-[600px] md:text-lg">
Software Engineer and builder. I love working on enhancing performance for web application & data heavy frontends.
</div>
  </div>

<img class="size-24 rounded-full" src="https://media.licdn.com/dms/image/v2/D4D03AQEScgPoSCp05w/profile-displayphoto-shrink_800_800/profile-displayphoto-shrink_800_800/0/1686298937000?e=1768435200&v=beta&t=KB4Ef_-5xY3s45yjJwqiXkK3iuBIxsPRfAxpyvKSztA"/>

</div>

<section id="about" class="mt-10">
   <div style="opacity: 1; filter: blur(0px); transform: translateY(-6px);">
      <h2 class="text-xl font-bold">About</h2>
   </div>
   <div style="opacity: 1; filter: blur(0px); transform: translateY(-6px);">
      <div class="prose max-w-full text-pretty font-sans text-sm text-muted-foreground dark:prose-invert">
         <p>I have a <a href="/#education">computer science degree</a> and <a href="/#work">4 YoE in software engineering</a>, but I'm an curious programmer.</p>
      </div>
   </div>
</section>

<section id='work' class="mt-10 flex min-h-0 flex-col gap-y-3">
  <div style="opacity: 1; filter: blur(0px); transform: translateY(-6px);">
      <h2 class="text-xl font-bold">Work</h2>
  </div>
  <div style="opacity: 1; filter: blur(0px); transform: translateY(-6px);">
   <a class="block cursor-pointer" href="https://hirehunch.com/">
      <div class="flex">
         <div class="flex-none"><span class="relative flex shrink-0 overflow-hidden rounded-full border size-12 m-auto bg-muted-background dark:bg-foreground"><img class="aspect-square h-full w-full object-contain" alt="HireHunch" src="https://media.glassdoor.com/sql/7242320/hirehunch-squareLogo-1695028953378.png"></span></div>
         <div class="flex-grow ml-4 items-center flex-col group">
            <div class="flex flex-col">
               <div class="flex items-center justify-between gap-x-2 text-base">
                  <h3 class="inline-flex items-center justify-center font-semibold leading-none text-xs sm:text-sm">
                     HireHunch
                     <span class="inline-flex gap-x-1"></span>
                     <!-- <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-chevron-right size-4 translate-x-0 transform opacity-0 transition-all duration-300 ease-out group-hover:translate-x-1 group-hover:opacity-100 rotate-0">
                        <path d="m9 18 6-6-6-6"></path>
                     </svg> -->
                  </h3>
                  <div class="text-xs sm:text-sm tabular-nums text-muted-foreground text-right">June 2022 - May 2023</div>
               </div>
               <div class="font-sans text-xs">Software Engineer</div>
            </div>
         </div>
      </div>
   </a>
</div>
<div style="opacity: 1; filter: blur(0px); transform: translateY(-6px);">
   <a class="block cursor-pointer" href="https://houseofx.in/">
      <div class="flex">
         <div class="flex-none"><span class="relative flex shrink-0 overflow-hidden rounded-full border size-12 m-auto bg-muted-background dark:bg-foreground"><img class="aspect-square h-full w-full object-contain" alt="HireHunch" src="https://media.licdn.com/dms/image/v2/D4D0BAQEX9rchNnpXJQ/company-logo_100_100/company-logo_100_100/0/1681303219316/house_of_x_01_logo?e=1768435200&v=beta&t=a64K9jHlCOVLpY5p6AvQ40HLhaW5EK04qV5zB9LT9zk"></span></div>
         <div class="flex-grow ml-4 items-center flex-col group">
            <div class="flex flex-col">
               <div class="flex items-center justify-between gap-x-2 text-base">
                  <h3 class="inline-flex items-center justify-center font-semibold leading-none text-xs sm:text-sm">
                     House Of X
                     <span class="inline-flex gap-x-1"></span>
                     <!-- <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-chevron-right size-4 translate-x-0 transform opacity-0 transition-all duration-300 ease-out group-hover:translate-x-1 group-hover:opacity-100 rotate-0">
                        <path d="m9 18 6-6-6-6"></path>
                     </svg> -->
                  </h3>
                  <div class="text-xs sm:text-sm tabular-nums text-muted-foreground text-right">May 2023 - Present</div>
               </div>
               <div class="font-sans text-xs">Software Engineer</div>
            </div>
         </div>
      </div>
   </a>
</div>
</section>

<section id='education' class="mt-10 flex min-h-0 flex-col gap-y-3"> 
   <div style="opacity: 1; filter: blur(0px); transform: translateY(-6px);">
      <h2 class="text-xl font-bold">Education</h2>
  </div>
  <div style="opacity: 1; filter: blur(0px); transform: translateY(-6px);">
   <a class="block cursor-pointer" href="https://houseofx.in/">
      <div class="flex">
         <div class="flex-none"><span class="relative flex shrink-0 overflow-hidden rounded-full border size-12 m-auto bg-muted-background dark:bg-foreground"><img class="aspect-square h-full w-full object-contain" alt="HireHunch" src="https://media.licdn.com/dms/image/v2/D560BAQHmq3eeLymIdA/company-logo_200_200/B56ZkJ8zZ0G0AI-/0/1756808558665/presidency_university_india_logo?e=1768435200&v=beta&t=u8V989U30ggTAztNRTrpHKWx2c3OUeHaRLYcFJZU48M"></span></div>
         <div class="flex-grow ml-4 items-center flex-col group">
            <div class="flex flex-col">
               <div class="flex items-center justify-between gap-x-2 text-base">
                  <h3 class="inline-flex items-center justify-center font-semibold leading-none text-xs sm:text-sm">
                     Presidency University
                     <span class="inline-flex gap-x-1"></span>
                     <!-- <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-chevron-right size-4 translate-x-0 transform opacity-0 transition-all duration-300 ease-out group-hover:translate-x-1 group-hover:opacity-100 rotate-0">
                        <path d="m9 18 6-6-6-6"></path>
                     </svg> -->
                  </h3>
                  <div class="text-xs sm:text-sm tabular-nums text-muted-foreground text-right">2018 - 2022</div>
               </div>
               <div class="font-sans text-xs">Computer Science</div>
            </div>
         </div>
      </div>
   </a>
</div>
  <div style="opacity: 1; filter: blur(0px); transform: translateY(-6px);">
   <a class="block cursor-pointer" href="https://houseofx.in/">
      <div class="flex">
         <div class="flex-none"><span class="relative flex shrink-0 overflow-hidden rounded-full border size-12 m-auto bg-muted-background dark:bg-foreground"><img class="aspect-square h-full w-full object-contain" alt="HireHunch" src="https://bishopcottonboysschool.edu.in/sites/default/files/footer_logo1.png"></span></div>
         <div class="flex-grow ml-4 items-center flex-col group">
            <div class="flex flex-col">
               <div class="flex items-center justify-between gap-x-2 text-base">
                  <h3 class="inline-flex items-center justify-center font-semibold leading-none text-xs sm:text-sm">
                     Bishop Cotton Boys&apos; School
                     <span class="inline-flex gap-x-1"></span>
                     <!-- <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-chevron-right size-4 translate-x-0 transform opacity-0 transition-all duration-300 ease-out group-hover:translate-x-1 group-hover:opacity-100 rotate-0">
                        <path d="m9 18 6-6-6-6"></path>
                     </svg> -->
                  </h3>
                  <div class="text-xs sm:text-sm tabular-nums text-muted-foreground text-right">2016 - 2018</div>
               </div>
               <div class="font-sans text-xs">ISC</div>
            </div>
         </div>
      </div>
   </a>
</div>
</section>

<section id='education' class="mt-10 flex min-h-0 flex-col gap-y-3"> 
   <div style="opacity: 1; filter: blur(0px); transform: translateY(-6px);">
      <h2 class="text-xl font-bold">Skills</h2>
  </div>
  <div class="flex flex-wrap gap-1"><div style="opacity: 1; filter: blur(0px); transform: translateY(-6px);"><div class="inline-flex items-center rounded-md border px-2.5 py-0.5 text-xs font-semibold transition-colors focus:outline-none focus:ring-2 focus:ring-ring focus:ring-offset-2 border-transparent bg-primary text-primary-foreground shadow hover:bg-primary/80">React</div></div><div style="opacity: 1; filter: blur(0px); transform: translateY(-6px);"><div class="inline-flex items-center rounded-md border px-2.5 py-0.5 text-xs font-semibold transition-colors focus:outline-none focus:ring-2 focus:ring-ring focus:ring-offset-2 border-transparent bg-primary text-primary-foreground shadow hover:bg-primary/80">Next.js</div></div><div style="opacity: 1; filter: blur(0px); transform: translateY(-6px);"><div class="inline-flex items-center rounded-md border px-2.5 py-0.5 text-xs font-semibold transition-colors focus:outline-none focus:ring-2 focus:ring-ring focus:ring-offset-2 border-transparent bg-primary text-primary-foreground shadow hover:bg-primary/80">Typescript</div></div><div style="opacity: 1; filter: blur(0px); transform: translateY(-6px);"><div class="inline-flex items-center rounded-md border px-2.5 py-0.5 text-xs font-semibold transition-colors focus:outline-none focus:ring-2 focus:ring-ring focus:ring-offset-2 border-transparent bg-primary text-primary-foreground shadow hover:bg-primary/80">Node.js</div></div><div style="opacity: 1; filter: blur(0px); transform: translateY(-6px);"><div class="inline-flex items-center rounded-md border px-2.5 py-0.5 text-xs font-semibold transition-colors focus:outline-none focus:ring-2 focus:ring-ring focus:ring-offset-2 border-transparent bg-primary text-primary-foreground shadow hover:bg-primary/80">Go</div></div><div style="opacity: 1; filter: blur(0px); transform: translateY(-6px);"><div class="inline-flex items-center rounded-md border px-2.5 py-0.5 text-xs font-semibold transition-colors focus:outline-none focus:ring-2 focus:ring-ring focus:ring-offset-2 border-transparent bg-primary text-primary-foreground shadow hover:bg-primary/80">Python</div></div><div style="opacity: 1; filter: blur(0px); transform: translateY(-6px);"><div class="inline-flex items-center rounded-md border px-2.5 py-0.5 text-xs font-semibold transition-colors focus:outline-none focus:ring-2 focus:ring-ring focus:ring-offset-2 border-transparent bg-primary text-primary-foreground shadow hover:bg-primary/80">Postgres</div></div><div style="opacity: 1; filter: blur(0px); transform: translateY(-6px);"></div><div style="opacity: 1; filter: blur(0px); transform: translateY(-6px);"><div class="inline-flex items-center rounded-md border px-2.5 py-0.5 text-xs font-semibold transition-colors focus:outline-none focus:ring-2 focus:ring-ring focus:ring-offset-2 border-transparent bg-primary text-primary-foreground shadow hover:bg-primary/80">Docker</div></div></div>
</section>



<div class="pointer-events-none fixed inset-x-0 bottom-0 z-30 mx-auto mb-4 flex origin-bottom h-full max-h-14">
    <div class="fixed bottom-0 inset-x-0 h-16 w-full bg-background to-transparent backdrop-blur-lg [-webkit-mask-image:linear-gradient(to_top,black,transparent)] dark:bg-background"></div>
    <div class="w-max p-2 rounded-full border z-50 pointer-events-auto relative mx-auto flex min-h-full h-full items-center px-1 bg-background [box-shadow:0_0_0_1px_rgba(0,0,0,.03),0_2px_4px_rgba(0,0,0,.05),0_12px_24px_rgba(0,0,0,.05)] transform-gpu dark:[border:1px_solid_rgba(255,255,255,.1)] dark:[box-shadow:0_-20px_80px_-20px_#ffffff1f_inset]">
        <div class="flex aspect-square cursor-pointer items-center justify-center rounded-full" style="width: 40px;">
            <a class="inline-flex items-center justify-center whitespace-nowrap text-sm font-medium transition-colors focus-visible:outline-none focus-visible:ring-1 focus-visible:ring-ring disabled:pointer-events-none disabled:opacity-50 hover:bg-accent hover:text-accent-foreground rounded-full size-12" data-state="closed" href="/">
                <House/>
            </a>
        </div>
        <!-- <div class="flex aspect-square cursor-pointer items-center justify-center rounded-full" style="width: 40px;">
            <a class="inline-flex items-center justify-center whitespace-nowrap text-sm font-medium transition-colors focus-visible:outline-none focus-visible:ring-1 focus-visible:ring-ring disabled:pointer-events-none disabled:opacity-50 hover:bg-accent hover:text-accent-foreground rounded-full size-12" data-state="closed" href="/blog">
                <BookMarked/>
            </a>
        </div> -->
        <div data-orientation="vertical" role="none" class="shrink-0 bg-border w-[1px] h-full"></div>
        <div class="flex aspect-square cursor-pointer items-center justify-center rounded-full" style="width: 40px;">
            <a class="inline-flex items-center justify-center whitespace-nowrap text-sm font-medium transition-colors focus-visible:outline-none focus-visible:ring-1 focus-visible:ring-ring disabled:pointer-events-none disabled:opacity-50 hover:bg-accent hover:text-accent-foreground rounded-full size-12" href="https://github.com/Kevin-Solomon">
                <Github/>
            </a>
        </div>
        <div class="flex aspect-square cursor-pointer items-center justify-center rounded-full" style="width: 40px;">
            <a class="inline-flex items-center justify-center whitespace-nowrap text-sm font-medium transition-colors focus-visible:outline-none focus-visible:ring-1 focus-visible:ring-ring disabled:pointer-events-none disabled:opacity-50 hover:bg-accent hover:text-accent-foreground rounded-full size-12" data-state="closed" href="https://www.linkedin.com/in/kevin-solomon7/">
               <Linkedin/>
            </a>
        </div>
        <!-- <div class="flex aspect-square cursor-pointer items-center justify-center rounded-full" style="width: 40px;">
            <a class="inline-flex items-center justify-center whitespace-nowrap text-sm font-medium transition-colors focus-visible:outline-none focus-visible:ring-1 focus-visible:ring-ring disabled:pointer-events-none disabled:opacity-50 hover:bg-accent hover:text-accent-foreground rounded-full size-12" data-state="closed" href="https://x.com/yang_frog">
                <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" class="size-4">
                    <title>X</title>
                    <path fill="currentColor" d="M18.901 1.153h3.68l-8.04 9.19L24 22.846h-7.406l-5.8-7.584-6.638 7.584H.474l8.6-9.83L0 1.154h7.594l5.243 6.932ZM17.61 20.644h2.039L6.486 3.24H4.298Z"></path>
                </svg>
            </a>
        </div> -->
        <div data-orientation="vertical" role="none" class="shrink-0 bg-border w-[1px] h-full py-2" ></div>
        <div class="flex aspect-square cursor-pointer items-center justify-center rounded-full" style="width: 40px;">
            <button onclick={toggleMode} class="inline-flex items-center justify-center whitespace-nowrap text-sm font-medium transition-colors focus-visible:outline-none focus-visible:ring-1 focus-visible:ring-ring disabled:pointer-events-none disabled:opacity-50 hover:bg-accent hover:text-accent-foreground h-9 w-9 rounded-full px-2" type="button">
                <Sun
    class="h-[1.2rem] w-[1.2rem] scale-100 rotate-0 !transition-all dark:scale-0 dark:-rotate-90"
  />
  <Moon
    class="absolute h-[1.2rem] w-[1.2rem] scale-0 rotate-90 !transition-all dark:scale-100 dark:rotate-0"
  />
            </button>
        </div>
    </div>
</div>

</main>
