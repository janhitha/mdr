<template>
  <div>
  <div class="border border-green-500 bg-gray-300 py-6">
      <div class="relative flex flex-wrap container">
   <div class="absolute right-0 flex flex-wrap ">
    <span class="pl-2 rounded">   
    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="#3b5998" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-facebook">
    <path d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"><animate dur="2s" values="#000000; #4e86b1; #000000" keyTimes="0; 0.5; 1" attributeName="fill" repeatCount="indefinite"/>
        </path></svg>
    </span>
    <span class="pl-2">
   <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="#00acee" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-twitter">
   <path d="M23 3a10.9 10.9 0 0 1-3.14 1.53 4.48 4.48 0 0 0-7.86 3v1A10.66 10.66 0 0 1 3 4s-4 9 5 13a11.64 11.64 0 0 1-7 2c9 5 20 0 20-11.5a4.5 4.5 0 0 0-.08-.83A7.72 7.72 0 0 0 23 3z">
    <animate fill="freeze" dur="0.1s" to="#00acee" from="white" attributeName="fill" begin="mouseover"/>
    <animate fill="freeze" dur="0.1s" to="white" from="#00acee" attributeName="fill" begin="mouseout"/>   
    </path></svg>
    </span>
    <span class="pl-2">
    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="#3f729b" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-instagram"><rect x="2" y="2" width="20" height="20" rx="5" ry="5"></rect><path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"></path><line x1="17.5" y1="6.5" x2="17.51" y2="6.5"></line></svg>
   </span>
   <span class="pl-2">
       <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="#0e76a8" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-linkedin"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"></path><rect x="2" y="9" width="4" height="12"></rect><circle cx="4" cy="4" r="2"></circle></svg>
   </span> 
   <span class="pl-2">
   <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="#c4302b" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-youtube"><path d="M22.54 6.42a2.78 2.78 0 0 0-1.94-2C18.88 4 12 4 12 4s-6.88 0-8.6.46a2.78 2.78 0 0 0-1.94 2A29 29 0 0 0 1 11.75a29 29 0 0 0 .46 5.33A2.78 2.78 0 0 0 3.4 19c1.72.46 8.6.46 8.6.46s6.88 0 8.6-.46a2.78 2.78 0 0 0 1.94-2 29 29 0 0 0 .46-5.25 29 29 0 0 0-.46-5.33z"></path><polygon points="9.75 15.02 15.5 11.75 9.75 8.48 9.75 15.02"></polygon></svg>  
   </span> 
       </div>
    </div>
  </div> 
  <div class="flex mb-2 lg:w-full container mx-auto">
      <div class="w-1/2 inline-block text-gray-900 font-semibold text-left px-4 py-2 m-2">
      <strong>
        <g-link class="font-bold text-4xl text-gray-900 font-family:open-sans" to="/">{{ $static.metadata.siteName }}</g-link>
      </strong>
      </div>
      <div class="menuheader">
          <g-link to="/">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="white" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-home">
          <path d="M3 9l9-7 9 7v11a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z"></path><polyline points="9 22 9 12 15 12 15 22"></polyline></svg>
          </g-link>
      </div>
      <div class="menuheader">
          <g-link to="/about">About</g-link>
      </div>
      <div class="menuheader">
          <g-link to="/contact">Contact</g-link>
      </div>
      <div class="mt-4">
     <g-link to="/login">  
      <button class="border border-blue-500 hover:bg-blue-400 text-gray-800 font-bold py-2 px-2 rounded inline-flex items-center">
      <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-log-in"><path d="M15 3h3a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2h-4"></path><polyline points="10 17 15 12 10 7"></polyline>
      <line x1="15" y1="12" x2="1" y2="12"></line></svg> 
      <span class="bg-transparent hover:text-black px-1">Login</span>
      </button></g-link>
      </div>
  </div>
  <div class="bg-green-400 border border-blue-500 w-full"></div> 
  </div>
</template>


<static-query>
query {
  metadata {
    siteName 
  }
}
</static-query>

<style scoped>
.menuheader {
    display: inline-block;
    padding-right: 1rem;
    padding-left: 1rem;
    padding-top: 1rem;
    padding-bottom: 0.5rem;
    font-weight: 600;
    margin: 0.5rem;
    color: #1a202c;
    text-align: center;
}
</style>
