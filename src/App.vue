<template>
  <div>

    <!-- Foto -->
    <div class="flex justify-center">
      <img class="w-3/4 mt-24" src="./img/foto1.png">
    </div>
    
    
    <!-- Texto -->
    
    <div class="flex">
      <p class="text-lg font-bold ml-12 mt-4">
        Studio Location
        </p>
    </div>
     <div class="flex">
      <p class="text-sm font-thin ml-12">
      Check our Studio Location  
       </p>
    </div>


    <!-- Mapa -->

    <div>
      <div class="flex justify-center mt-6">
        <img class="w-80 border-black border " src="./img/foto2.png">
      </div>
    </div>
    <div class="flex ">
      <p class="text-medium font-medium ml-8 mt-4">
        Studio Location
      </p>
    </div>

    <!-- Location -->
    <div class="flex">
      <img class="ml-8 mt-4 w-4" src="./img/foto3.png">
      <div class="absolute">
      <p class="mt-4 ml-16 text-medium">
        Carl-Reuther-Str. 1 - 68305, Mannheim
      </p>
      </div>
    </div>

    <!-- Hours -->
     <div class="flex mt-8">
      <div class="ml-8 font-medium">Our hours</div>
      <div class="absolute">
         <img class="ml-10 mt-10 w-6 m-0" src="./img/foto4.png">
         <img class="ml-10 mt-4 w-6 m-0" src="./img/foto4.png">
      </div>
      <div class="absolute">
        <p class="mt-10 ml-20 text-medium">
           Mon - Fr 17:00 - 22:00
        </p>
        <p class="mt-4 ml-20 text-medium">
           Sa - So 11:00 - 22:00
        </p>
      </div>
      
    </div>
    <!-- Contact -->
    <div class="flex">
        <p class="font-medium ml-8 mt-28">Contact Info</p>
      <div class="absolute">
        <img class="inline-block ml-10 w-6" src="./img/foto5.png">
          <div class="inline-block ml-10 mt-44 m-0">0176 43406843</div>  
      </div>
      <div class="absolute mt-56">
        <img class="inline-block ml-10 w-6" src="./img/foto6.png">
        <div class="inline-block ml-10">animo@dance.com</div>
      </div>
    </div>
    
    <!-- Linea divisora -->
    <div class="flex justify-center">
      <img class="mt-40" src="./img/foto7.png">
    </div>
  
  
  </div>

  <!-- Seccion 2 -->
  <div>
    <div class="inline-block">
      <p class="text-lg ml-8 mt-6"> Get in Touch</p>
      <p class="text-medium font-thin ml-8"> Ask question</p>
    </div>

    <!-- Contact Form -->
    <div class="mt-8">
    <div class="flex flex-wrap mb-6">
    <div class="w-full px-3 mb-6">
      <label class="block tracking-wide text-black text-sm font-semibold mb-2">
        Full Name
      </label>
      <input class="appearance-none block w-full bg-gray-100 text-black border border-gray rounded py-3 px-4 mb-3 leading-tight focus:outline-none focus:bg-white" type="text" placeholder="Your Full Name">
      <p class="text-red-500 text-xs italic">Please fill out this field.</p>
    </div>
    <div class="w-full px-3">
      <label class="block tracking-wide text-black text-sm font-semibold mb-2" placeholder="Your Full Name">
        Phone Number
      </label>
      <input class="appearance-none block w-full bg-gray-100 text-gray-700 border border-gray-200 rounded py-3 px-4 leading-tight focus:outline-none focus:bg-white focus:border-gray-500" type="text" placeholder="+49...">
    </div>
  </div>
  <div class="flex flex-wrap mb-6">
    <div class="w-full px-3">
      <label class="block uppercase tracking-wide text-black text-xs font-bold mb-2">
        E-mail
      </label>
      <input class="appearance-none block w-full bg-gray-100 text-gray-700 border border-gray-200 rounded py-3 px-4 mb-3 leading-tight focus:outline-none focus:bg-white focus:border-gray-500" type="email" placeholder="animo@dance.com">
    </div>
  </div>
  
  <!-- Message -->
  
  <div class="flex flex-wrap  mb-6">
    <div class="w-full px-3">
      <label class="block uppercase tracking-wide text-black text-xs font-bold mb-2">
        Message
      </label>
      <textarea class="no-resize appearance-none block w-full bg-gray-100 text-gray-700 border border-gray-100 rounded py-3 px-4 mb-3 leading-tight focus:outline-none focus:bg-white focus:border-gray-500 h-48 resize-none" placeholder="Try to describe you problem the best is possible.."></textarea>
    </div>
    <div class="flex items-center justify-between">
      <button class="bg-green-500 ml-4 text-white font-bold py-2 px-4 rounded" type="button">
        Send Message
      </button>
    </div>
  </div>
  </div>
</div>

</template>


<style>

</style>
