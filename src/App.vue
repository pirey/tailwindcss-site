<script>
import Separator from './components/Separator.vue'

export default {
  components: {
    Separator
  }
}
</script>

<template>
  <div class="w-full max-w-lg mx-auto mt-24">
    <header class="max-w-lg mx-auto fixed inset-x-0 top-0 z-50 bg-gray-100 flex items-center justify-between p-6 border-b border-gray-300">
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

    <Separator class="relative z-10" />

    <section class="px-6 pt-16 pb-40 bg-white">
      <h2 class="text-2xl leading-none">Most CSS frameworks do too much.</h2>
      <p class="mt-6 text-gray-700 text-sm">They come with all sorts of predesigned components like buttons, cards, and alerts that might help you move quickly at first, but cause more pain than they cure when it comes time to make your site stand out with a custom design.</p>
      <p class="mt-6 text-gray-700 text-sm">Tailwind is different</p>
      <p class="mt-6 text-gray-700 text-sm">Instead of opinionated predesigned components, Tailwind provides low-level utility classes that let you build completely custom designs without ever leaving your HTML.</p>

      <div class="mt-6 p-6 rounded-lg border border-gray-400">
        <img class="w-auto max-w-full h-64 object-cover rounded-lg" src="https://images.unsplash.com/photo-1556740738-b6a63e27c4df?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=448&q=80" alt="business woman" />
        <div class="mt-4 uppercase text-indigo-500 tracking-wide text-xs font-bold">Marketing</div>
        <h2 class="mt-1 font-semibold leading-tight">Finding customers for your new business</h2>
        <p class="mt-2 text-gray-600 text-sm">Getting a new business off the ground is a lot of hard work. Here are five ideas you can use to find your first customers.</p>
      </div>

      <p class="mt-6 text-gray-700 text-sm">If you're sick of fighting the framework, overriding unwanted styles, and battling specificity wars, Tailwind was made for you.</p>

      <a class="inline-block mt-6 text-sm underline text-blue-500 hover:text-blue-700" href="#">Learn more about Tailwind's utility-first workflow →</a>

      <hr class="h-0 border border-gray-300 my-16" />

      <h2 class="text-2xl leading-none">Responsive to the core</h2>
      <p class="mt-6 text-gray-700 text-sm">Every Tailwind utility also comes with responsive variants, making it extremely easy to build responsive interfaces without resorting to custom CSS.</p>
      <p class="mt-6 text-gray-700 text-sm">Tailwind uses an intuitive <span class="inline-block px-1 tracking-wide bg-gray-100 text-indigo-700">{screen}:</span> prefix that makes it easy to notice responsive classes in your markup while keeping the original class name recognizable and intact.</p>

      <div class="mt-6 p-4 rounded-lg border border-gray-400">
        <div class="bg-gray-200 flex p-2">
          <div class="flex justify-center items-center text-sm h-8 w-8 text-gray-700 bg-gray-400">1</div>
          <div class="flex justify-center items-center text-sm ml-2 h-8 w-8 text-gray-700 bg-gray-400">2</div>
          <div class="flex justify-center items-center text-sm ml-2 h-8 w-8 text-gray-700 bg-gray-400">3</div>
        </div>
      </div>

      <a class="inline-block mt-6 text-sm underline text-blue-500 hover:text-blue-700" href="#">Learn more about responsive design with Tailwind →</a>
    </section>

  </div>
</template>
