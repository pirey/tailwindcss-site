<template>
  <div class="w-full max-w-lg mx-auto">
    <header class="flex items-center justify-between p-6 border-b border-gray-300">
      <a class="inline-block outline-none" href="#">
        <svg class="w-10 h-10 block md:hidden" viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg"><path d="M13.5 11.1C15.3 3.9 19.8.3 27 .3c10.8 0 12.15 8.1 17.55 9.45 3.6.9 6.75-.45 9.45-4.05-1.8 7.2-6.3 10.8-13.5 10.8-10.8 0-12.15-8.1-17.55-9.45-3.6-.9-6.75.45-9.45 4.05zM0 27.3c1.8-7.2 6.3-10.8 13.5-10.8 10.8 0 12.15 8.1 17.55 9.45 3.6.9 6.75-.45 9.45-4.05-1.8 7.2-6.3 10.8-13.5 10.8-10.8 0-12.15-8.1-17.55-9.45-3.6-.9-6.75.45-9.45 4.05z" transform="translate(5 16)" fill="url(#logoMarkGradient)" fill-rule="evenodd"/><defs><linearGradient x1="0%" y1="0%" y2="100%" id="logoMarkGradient"><stop stop-color="#2298BD"/><stop offset="1" stop-color="#0ED7B5"/></linearGradient></defs></svg>
      </a>
      <div class="flex items-center justify-between text-sm bg-white px-3 py-2 shadow-md rounded-lg flex-grow mx-4">
        <svg class="fill-current pointer-events-none text-gray-600 w-4 h-4" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"><path d="M12.9 14.32a8 8 0 111.41-1.41l5.35 5.33-1.42 1.42-5.33-5.34zM8 14A6 6 0 108 2a6 6 0 000 12z"/></svg>
        <input class="ml-3 flex-grow focus:outline-none" placeholder='Search the docs (Press &quot;/&quot; to focus)' />
      </div>
      <button class="outline-none active:outline-none focus:outline-none">
        <svg class="fill-current w-4 h-4 text-gray-500" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"><path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/></svg>
      </button>
    </header>

    <section class="px-6 pt-16 pb-40">
      <h1 class="leading-tight text-gray-800 text-2xl">A utility-first CSS framework for <span class="text-teal-500">rapidly building custom designs.</span></h1>
      <p class="mt-6 text-gray-600 text-sm leading-relaxed">Tailwind CSS is a highly customizable, low-level CSS framework that gives you all of the building blocks you need to build bespoke designs without any annoying opinionated styles you have to fight to override. </p>
      <div class="mt-6">
        <button class="btn btn-teal" type="button">Get Started</button>
        <button class="ml-3 btn">Why Tailwind?</button>
      </div>
    </section>
  </div>
</template>
