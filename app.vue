<script setup lang="ts">
useHead({
  title: 'Janzell Jurilla | Software Developer',
  meta: [
    {
      name: 'description',
      content: 'Janzell Jurilla | Software Developer'
    }
  ]
})
</script>
<template>
  <div class="bg-cover bg-center h-screen"
    style="background-image: url('https://images.unsplash.com/photo-1682687220208-22d7a2543e88?q=80&w=1550&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDF8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D')">
    <main class="bg-white h-full mx-auto max-w-7xl font-sans">
      <header class="bg-purple-950 my-5 p-10 text-center rounded-t-md">
        <p class="bg-red-500 rounded-full px-2 py-1 mb-3 inline-block text-2xl font-sans text-white">JJ</p>
        <h1 class="text-4xl font-bold uppercase tracking-widest text-amber-300 leading-7">
          Janzell Jurilla <br>
          <span class="text-white text-xs">Software Developer</span>
        </h1>
      </header>

      <!-- Create a Two column with 30-70 ratio -->
      <section class="flex px-5 gap-4 text-gray-700">
        <aside class="w-1/4 divide-y divide-dashed">
          <div class="mb-5 py-5">
            <h2 class="text-xl uppercase pb-4 tracking-widest">Summary</h2>
            <p class="text-justify text-sm">
              Bachelor of Science in Information Management graduate with Cum Laude honors, offering nearly 7 years of
              expertise as an IT enthusiast specializing in web and software development. Adept at leveraging cutting-edge
              technologies to address complex challenges and excelling in the design of multi-platform applications. Key
              strengths include proficiency in Web-based Application development, Database Design, Software Development,
              Cross-platform Application development, and Project Management.
            </p>
          </div>
          <div class="mb-5 py-5">
            <h2 class="text-xl uppercase pb-4 tracking-widest">Skills</h2>
            <p class="text-justify text-sm">
              Bachelor of Science in Information Management graduate with Cum Laude honors, offering nearly 7 years of
              expertise as an IT enthusiast specializing in web and software development. Adept at leveraging cutting-edge
              technologies to address complex challenges and excelling in the design of multi-platform applications. Key
              strengths include proficiency in Web-based Application development, Database Design, Software Development,
              Cross-platform Application development, and Project Management.
            </p>
          </div>
        </aside>
        <article class="w-3/4 border-s ps-4 text-sm">
          <div class="mb-5 py-5">
            <h2 class="text-xl uppercase pb-4 tracking-widest">Professional Experience</h2>
            <div class="flex flex-col">
              <div class="mb-3">
                <div class="font-bold">SENIOR SOFTWARE ENGINEER</div>
                <p class="text-gray-400">vWise Inc. | 2021.05 - Present</p>
                <p class="mt-4">In various team roles, actively participated in API pattern implementation (SOAP, REST), authored standard documents for version control, coding, and task management, and contributed to the successful realization of impactful projects. Eager to bring a wealth of experience and skills to a dynamic development team.</p>
              </div>
            </div>
          </div>
        </article>
      </section>
    </main>
  </div>
</template>
