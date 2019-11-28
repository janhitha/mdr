<template>
  <div>
    <menuheader /> 
     <transition name="fade" appear>
       <main>
        <slot class="container mx-auto"/>
       </main>
     </transition>
    <menufooter /> 
  </div>
</template>


<script>
import menuheader from '~/components/Header.vue'
import menufooter from '~/components/Footer.vue'
export default {
  components: {
    menuheader,
    menufooter
  }
  
}
</script>

<style>
body {
  font-family: -apple-system,system-ui,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,sans-serif;
  margin:0;
  padding:0;
  line-height: 1.5;
}

.fade-enter-active {
  transition: opacity .5s;
}

.fade-enter {
  opacity: 0;
}
</style>