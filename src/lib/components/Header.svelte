<script>
  import Icon from '@iconify/svelte';
</script>

<!-- Tailwind Flowbite-->


<header class="">
<nav class="bg-orange-950">
  <div class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-4">
    <a href="/" class="flex items-center space-x-3 rtl:space-x-reverse">
      
    
      <Icon class="animate-bounce" icon="fluent-mdl2:my-movies-t-v" color="red" width="90" height="90" />
        
        <span class="font-[HedvigLettersSerif] self-center text-5xl font-semibold whitespace-nowrap dark:text-white">Marvel's Collection Panel</span>
    </a>
    
    <div class="hidden w-full md:block md:w-auto" id="navbar-default">
      <ul class="md:flex items-center gap-x-8">
        <button type="button" class="text-white bg-gradient-to-r from-red-400 via-red-500 to-red-600 hover:bg-gradient-to-br focus:ring-4 focus:outline-none focus:ring-red-300 dark:focus:ring-red-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2"><li>
          <a class="font-semibold text-black" href="/movies"><Icon icon="fluent-mdl2:my-movies-t-v" color="black" width="90" height="50" />Movies</a>
        </li></button>
        <button type="button" class="text-white bg-gradient-to-r from-red-400 via-red-500 to-red-600 hover:bg-gradient-to-br focus:ring-4 focus:outline-none focus:ring-red-300 dark:focus:ring-red-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2"> <li>
          <a class="font-semibold text-black" href="/list"><Icon icon="fluent-mdl2:my-movies-t-v" color="black" width="90" height="50" />List</a>
        </li></button>
        <button type="button" class="text-white bg-gradient-to-r from-red-400 via-red-500 to-red-600 hover:bg-gradient-to-br focus:ring-4 focus:outline-none focus:ring-red-300 dark:focus:ring-red-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2"> <li>
          <a class="font-semibold text-black" href="/about"><Icon icon="fluent-mdl2:my-movies-t-v" color="black" width="90" height="50" />About</a>
        </li></button>
      </ul>
    </div>
  </div>
</nav>
</header>







