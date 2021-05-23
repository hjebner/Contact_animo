<template>
  <div>

    <!-- Foto -->
    <div class="flex justify-center flex-shrink mx-2">
      <img class="w-screen mt-24 border rounded lg:w-full lg:mx-12 md:w-full md:mx-12 sm:w-screen sm:mx-4" src="./img/foto1.png">
    </div>
    
    
    <!-- Texto -->
    
    <div class="flex flex-wrap">
      <p class="text-lg font-bold ml-6 mt-4 lg:text-4xl lg:mt-10 lg:ml-12 md:mt-6 md:ml-12 sm:ml-10 md:text-2xl sm:text-xl">
        Studio Location
        </p>
    </div>
     <div class="flex flex-wrap">
      <p class="text-sm font-thin ml-6 lg:text-3xl lg:mt-2 lg:ml-12 md:ml-12 md:text-xl sm:ml-10 sm:text-xl">
      Check out the Map  
       </p>
    </div>


    <!-- Mapa -->

    <div>
      <div class="flex justify-center flex-shrink mt-6 mx-4">
        <img class="w-80 border-black border lg:w-2/3 lg:mt-10 sm:w-2/3 " src="./img/foto2.png">
      </div>
    </div>
    <div class="flex lg:mt-12 md:mt-8 sm:mt-4">
      <p class="text-medium font-medium ml-8 mt-4 lg:ml-12 lg:text-3xl md:text-2xl sm:text-2xl  ">
        Location
      </p>
    </div>

    <!-- Location -->
    <div class="flex flex-shrink">
      <svg class="w-6 h-6 mt-6 ml-8 fill-current text-green-600 lg:w-10 lg:h-10 md:w-8 md:h-8 sm:w-8 sm:h-8 sm:mt-10" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M5.05 4.05a7 7 0 119.9 9.9L10 18.9l-4.95-4.95a7 7 0 010-9.9zM10 11a2 2 0 100-4 2 2 0 000 4z" clip-rule="evenodd"></path></svg>
      <div class="absolute">
      <p class="mt-6 ml-16 text-medium lg:ml-28 md:ml-20 lg:text-3xl md:text-2xl sm:ml-20 sm:text-xl sm:mt-10 lg:mt-12">
        Carl-Reuther-Str. 1 - 68305, Mannheim
      </p>
      </div>
    </div>

    <!-- Hours -->
     <div class="flex mt-8 lg:mt-16">
      <div class="ml-8 font-medium lg:text-3xl md:text-2xl sm:text-2xl ">Our hours</div>
      <div class="absolute mt-4 lg:mt-12">
         <svg class="w-8 h-8 md:w-10 md:h-10 lg:w-12 lg:h-12 mt-10 ml-14 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
         <svg class="w-8 h-8 md:w-10 md:h-10 lg:w-12 lg:h-12 mt-4 lg:mt-8 ml-14 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
      </div>
      <div class="absolute mt-16 lg:mt-24 md:mt-14 sm:mt-14">
        <p class="inline mt-8 ml-28 text-medium lg:ml-32 md:ml-28 lg:text-3xl md:text-2xl sm:ml-28 sm:text-xl sm:mt-10">
           Mon - Fr 17:00 - 22:00
        </p>
        <p class="mt-6 ml-28 text-medium lg:ml-32 md:ml-28 lg:text-3xl md:text-2xl sm:ml-28 sm:text-xl sm:mt-6 lg:mt-10">
           Sa - So 11:00 - 22:00
        </p>
      </div>
      
    </div>

    <!-- Contact   -->
     <div class="flex mt-36 lg:mt-60 md:mt-40 sm:mt-34">
      <div class="ml-8 font-medium lg:text-3xl md:text-2xl sm:text-xl ">Contact Info</div>
      <div class="absolute mt-4 lg:mt-12">
         <svg class="w-8 h-8 md:w-10 md:h-10 lg:w-12 lg:h-12 mt-10 ml-14 fill-current text-green-600" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.773a11.037 11.037 0 006.105 6.105l.774-1.548a1 1 0 011.059-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 5V3z"></path></svg>
         <svg class="w-8 h-8 md:w-10 md:h-10 lg:w-12 lg:h-12 mt-4 lg:mt-8 ml-14 fill-current text-green-600" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M14.243 5.757a6 6 0 10-.986 9.284 1 1 0 111.087 1.678A8 8 0 1118 10a3 3 0 01-4.8 2.401A4 4 0 1114 10a1 1 0 102 0c0-1.537-.586-3.07-1.757-4.243zM12 10a2 2 0 10-4 0 2 2 0 004 0z" clip-rule="evenodd"></path></svg>
      </div>
      <div class="absolute mt-16 lg:mt-24 md:mt-14 sm:mt-14">
        <p class="inline mt-8 ml-28 text-medium lg:ml-32 md:ml-28 lg:text-3xl md:text-2xl sm:ml-28 sm:text-xl sm:mt-10">
           0176 43406843
        </p>
        <p class="mt-6 ml-28 text-medium lg:ml-32 md:ml-28 lg:text-3xl md:text-2xl sm:ml-28 sm:text-xl sm:mt-6 lg:mt-10">
           animo@dance.com
        </p>
      </div>
      
    </div>
    
    <!-- Linea divisora -->
    <div class="flex justify-center lg:mb-8 md:mb-4">
      <img class="mt-36 lg:mt-64 md:mt-48 sm:mt-36 w-screen h-1 mx-6" src="./img/foto7.png">
    </div>
  
  
  </div>

  <!-- Seccion 2 -->
  <div>
    <div class="inline-block">
      <p class="text-lg ml-8 mt-6 lg:text-4xl md:text-2xl sm:text-xl font-bold"> Get in Touch</p>
      <p class="text-medium font-thin ml-8 lg:text-3xl md:text-xl sm:text-xl"> Ask question</p>
    </div>

    <!-- Contact Form -->
    <div class="mt-8 mx-6">
    <div class="flex flex-wrap mb-6">
    <div class="w-full px-3 mb-6">
      <label class="block tracking-wide text-black text-sm  mb-2 lg:text-2xl md:text-xl sm:text-xl">
        Full Name
      </label>
      <input class="appearance-none block w-full bg-gray-100 text-black border border-gray rounded py-3 px-4 mb-3 leading-tight focus:outline-none focus:bg-white" type="text" placeholder="Your Full Name">
      <p class="text-red-500 text-xs italic">Please fill out this field.</p>
    </div>
    <div class="w-full px-3">
      <label class="block tracking-wide text-black text-sm mb-2 lg:text-2xl md:text-xl sm:text-xl" placeholder="Your Full Name">
        Phone Number
      </label>
      <input class="appearance-none block w-full bg-gray-100 text-gray-700 border border-gray-200 rounded py-3 px-4 leading-tight focus:outline-none focus:bg-white focus:border-gray-500" type="text" placeholder="+49...">
    </div>
  </div>
  <div class="flex flex-wrap mb-6">
    <div class="w-full px-3">
      <label class="block tracking-wide text-black text-xs mb-2 lg:text-2xl md:text-xl sm:text-xl">
        E-mail
      </label>
      <input class="appearance-none block w-full bg-gray-100 text-gray-700 border border-gray-200 rounded py-3 px-4 mb-3 leading-tight focus:outline-none focus:bg-white focus:border-gray-500" type="email" placeholder="animo@dance.com">
    </div>
  </div>
  
  <!-- Message -->
  
  <div class="flex flex-wrap  mb-6">
    <div class="w-full px-3">
      <label class="block tracking-wide text-black text-xs mb-2 lg:text-2xl md:text-xl sm:text-xl">
        Message
      </label>
      <textarea class="no-resize appearance-none block w-full bg-gray-100 text-gray-700 border border-gray-100 rounded py-3 px-4 mb-3 leading-tight focus:outline-none focus:bg-white focus:border-gray-500 h-48 resize-none" placeholder="Try to describe you problem the best is possible.."></textarea>
    </div>
    <div class="flex items-center justify-between mt-6">
      <button class="bg-green-600 ml-4 text-white font-bold py-2 px-4 rounded" type="button">
        Send Message
      </button>
    </div>
  </div>
  </div>
</div>

</template>


<style>

</style>
