<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  },

  data() {
  return {
    lastLogin: null
  }
},

// in a method
login() {
  this.lastLogin = new Date()
}
})
</script> 

<template>
<div class="wrapper">
  <!-- component -->
<div class="w-3/4 mx-auto mt-10">
  <div class="w-full shadow-2xl subpixel-antialiased rounded h-64 bg-black border-black mx-auto">
    <div class="flex items-center h-6 rounded-t bg-gray-100 border-b border-gray-500 text-center text-black" id="headerTerminal">
      <div class="flex ml-2 items-center text-center border-red-900 bg-red-500 shadow-inner rounded-full w-3 h-3" id="closebtn">
      </div>
      <div class="ml-2 border-yellow-900 bg-yellow-500 shadow-inner rounded-full w-3 h-3" id="minbtn">
      </div>
      <div class="ml-2 border-green-900 bg-green-500 shadow-inner rounded-full w-3 h-3" id="maxbtn">
      </div>
      <div class="mx-auto pr-16" id="terminaltitle">
        <p class="text-center text-sm">Terminal</p>
      </div>

    </div>
    <div class="pl-1 pt-1 h-auto  text-green-200 font-mono text-xs bg-black" id="console">

      <p class="pb-1">Hello Monz, today is the day...</p>
      <p class="pb-1">Before you enter check:</p>
      <p class="pb-1 text-center">Order flow</p>
      <p class="pb-1 text-center">Order block</p>
      <p class="pb-1 text-center">The risk</p>
      <p class="pb-1 text-center">...</p>
      <p class="pb-1 text-center">Focus</p>
      <p class="pb-1 text-center">...</p>
      <p class="pb-1 text-center">...</p>
    </div>
  </div> 
</div>
      <!-- component -->
      <div class="flex flex-col">
        <div></div>
        <h2 class="mb-4 text-2xl text-center mt-5 font-bold">Crypto dashboard</h2>

        <div class="mt-4 grid grid-cols-1 gap-4 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4">
          <div class="flex items-start rounded-xl bg-white p-4 shadow-lg">
            <div class="flex h-12 w-12 items-center justify-center rounded-full border border-orange-100 bg-orange-50">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-orange-400" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                <path stroke-linecap="round" stroke-linejoin="round" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z" />
              </svg>
            </div>

            <div class="ml-4">
              <h2 class="font-semibold">Monz</h2>
              <p class="mt-2 text-sm text-gray-500">Active now</p>
            </div>
          </div>
          <div class="flex items-start rounded-xl bg-white p-4 shadow-lg">
            <div class="flex h-12 w-12 items-center justify-center rounded-full border border-red-100 bg-red-50">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-red-400" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                <path stroke-linecap="round" stroke-linejoin="round" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.247 18 16.5 18c-1.746 0-3.332.477-4.5 1.253" />
              </svg>
            </div>

            <div class="ml-4">
              <h2 class="font-semibold">17 orders finished</h2>
              <p class="mt-2 text-sm text-gray-500">All time</p>
            </div>
          </div>
          <div class="flex items-start rounded-xl bg-white p-4 shadow-lg">
            <div class="flex h-12 w-12 items-center justify-center rounded-full border border-blue-100 bg-blue-50">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-blue-400" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                <path stroke-linecap="round" stroke-linejoin="round" d="M7 8h10M7 12h4m1 8l-4-4H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-3l-4 4z" />
              </svg>
            </div>

            <div class="ml-4">
              <h2 class="font-semibold">Settings</h2>
              <p class="mt-2 text-sm text-gray-500">General</p>
            </div>
          </div>

          
          
          <div class="flex items-start rounded-xl bg-white p-4 shadow-lg">
            <div class="flex h-12 w-12 items-center justify-center rounded-full border border-indigo-100 bg-indigo-50">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-indigo-400" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                <path stroke-linecap="round" stroke-linejoin="round" d="M7 8h10M7 12h4m1 8l-4-4H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-3l-4 4z" />
              </svg>
            </div>

            <div class="ml-4">
              <h2 class="font-semibold">50to5k</h2>
              <p class="mt-2 text-sm text-gray-500">Consistantly</p>
            </div>
          </div>
        </div>
      </div>
    </div>
</template>

