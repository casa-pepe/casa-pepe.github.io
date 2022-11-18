<template>
    <div class="fixed top-0 w-full z-40">
          <svg viewBox="0 0 100 100" preserveAspectRatio="none" class="w-full h-24" >
            <polygon points="0,0 100,0 100,100 0,100" />
          </svg>
          
          <div class="absolute top-0 left-0 right-0 m-auto w-48 text-white z-50">
            <CasaPepeLogo />
          </div>
          
          <div class="absolute md:top-5 md:left-5 top-3 left-3 w-48 text-gray-400 text-xs md:text-sm">
            <a href="tel:9079038865" class="p-2 rounded-md hover:bg-red-800  hover:text-white transition ease-in-out">(907)-903-8865</a>
          </div>

          <div class="absolute top-3 right-0 w-16 text-gray-400 flex">
            <a href="https://instagram.com/pepespaella" target="_blank">
                <Instagram width="24px" height="24px" />
              </a>

              <a href="https://www.facebook.com/pepespaella" target="_blank">
                <Facebook width="24px" height="24px" />
              </a>
          </div>

          <svg viewBox="0 0 100 100" preserveAspectRatio="none" class="w-full h-16 fill-current drop-shadow-lg" >
            <polygon id="highlight" class="transition-all ease-in-out duration-400" :class="highlightColor" points="0,0 100,0 100,20 50,65 0,20" />
            <polygon points="0,0 100,0 50,65" />
          </svg>

        </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default {
  props: {
    highlightColor: String
  }, 
  setup() {

  }
}
</script>
