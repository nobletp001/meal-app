<template>
  <header class="bg-white shadow h-16 flex justify-between items-stretch">
    <router-link
      :to="{ name: 'home' }"
      class="inline-flex items-center h-full px-5 text-orange-500 font-bold"
    >
      Home
    </router-link>
    <div class="flex items-center gap-1">
      <router-link
        :to="{ name: 'byName' }"
        class="inline-flex  text-xs md:text-lg items-center px-2 h-full transition-colors hover:bg-orange-500 hover:text-white"
      >
         <span class=" hidden md:inline">    Search</span>
       Meals
      </router-link>
      <router-link
        :to="{ name: 'byLetter' }"
        class="inline-flex  text-xs md:text-lg items-center px-2 h-full transition-colors hover:bg-orange-500 hover:text-white"
      >
          <span class=" hidden md:inline">  Meals By</span>
      Letter
      </router-link>
      <router-link
        :to="{ name: 'ingredients' }"
        class="inline-flex  text-xs md:text-lg items-center px-2 h-full transition-colors hover:bg-orange-500 hover:text-white"
      >
      <span class=" hidden md:inline">  Meals By</span> Ingredients
      </router-link>
    </div>
  </header>
</template>
