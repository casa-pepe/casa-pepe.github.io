<template>
    <div class="">
      <div 
        class="w-full relative bg-fixed bg-cover" 
        style="background-image: url('/banner5.jpg')"
        >
        
        <Header 
          :highlightColor="highlight" 
          />
        
        <div 
          class="relative bg-fixed bg-cover bg-center bg-no-repeat z-0 pt-40" 
          style="background-image:url('/duck-paella.jpg')"
          >
          
          <div class="
                flex flex-col md:flex-row 
                justify-center items-center md:items-start
                py-6 my-6
                bg-black bg-opacity-50 
                border-x-0 border-double border-2 border-yellow-500
                text-white font-semibold text-justify
            ">
            <div class="w-64 md:mr-12 pb-6 md:pb-0 ">
              Our brand of Paella began as an adventure in cooking inspired by biking through the Spanish countryside. It has evolved in the tradition of finding fresh, Alaskan ingredients and preparing them on site for the best experience.
            </div>
            <div class="w-64">
              We strive to provide a unique culinary experience in fantastic locations and settings. You may have tried our paella at music festivals, your farmer's market, a wedding, or any number of other events, either way we look forward to serving up the freshest food around. 
            </div>
          </div>
          
          <!-- coming soon start -->
          <svg viewBox="0 0 100 100" preserveAspectRatio="none" class="w-full h-8 text-black border-none" >
            <polygon class="fill-blue-600" points="0,100 100,100 50,25" />
          </svg>
          <div class="bg-blue-600 uppercase">
            <div class="m-auto w-fit">
             <h3 class="text-xl text-white">2025 Schedule coming soon!</h3>
            </div>
          </div>
          <svg ref="top"
            viewBox="0 0 100 100" preserveAspectRatio="none" class="w-full h-12 text-black" >
            <polygon class="fill-blue-600" points="0,0 100,0 50,65" />
          </svg>
          <!-- coming soon end -->

          <svg viewBox="0 0 100 100" preserveAspectRatio="none" class="w-full h-8 text-black border-none" >
            <polygon class="fill-rose-600" points="0,100 100,100 50,25" />
          </svg>
          <div class="bg-rose-600 uppercase">
            <div class="m-auto w-fit">
             <h3 class="text-xl text-white">Past Events</h3>
            </div>
          </div>

          <Event 
            startFillColor="fill-rose-600" 
            endFillColor="fill-indigo-700" 
            eventImage="/forest-fair-2022.jpg"
            eventTitle="Girdwood Forest Fair"
            eventDate="July 7th - 9th 2023"
            eventLocation="Girdwood, AK"
            eventLink="https://girdwoodforestfair.com/"
            bgImage="background-image: linear-gradient(to bottom, rgba(0, 0, 0, 0.9), rgba(0,0,0, 0.1)), url('/forest-fair-cropped.jpg')"
            />

          <Event 
            startFillColor="fill-indigo-700" 
            endFillColor="fill-red-700" 
            eventTitle="Bear Paw Festival"
            eventImage="/bear-paw-2023.png"
            eventDate="July 13 - 16 2023"
            eventLocation="Eagle River, AK"
            eventLink="https://www.bearpawfestival.org/"
            bgImage="background-image: linear-gradient(to bottom, rgba(0, 0, 0, 0.9), rgba(0,0,0, 0.1)), url('/bear-paw-bg.png'); background-position: center"
            />

            <Event 
              startFillColor="fill-red-700" 
              endFillColor="fill-yellow-700"               
              eventTitle="Salmonfest"
              eventDate="August 4th - 6th 2023"
              eventLocation="Ninilchik, AK"
              eventLink="https://salmonfestalaska.org/"
              bgImage="background-image: linear-gradient(to bottom, rgba(0, 0, 0, 0.9), rgba(0,0,0, 0.1)), url('/salmonfest-2022.jpg'); background-position: center"
              />

            <Event 
              startFillColor="fill-yellow-700" 
              endFillColor="fill-yellow-700"               
              eventTitle="Alaska State Fair"
              eventDate="August 18th - September 4th 2023"
              eventLocation="Palmer, AK"
              eventLink="https://www.alaskastatefair.org/site/#alaska-state-fair"
              bgImage="background-image: linear-gradient(to bottom, rgba(0, 0, 0, 0.9), rgba(0,0,0, 0.1)), url('/salmonfest-2022.jpg'); background-position: center"
              />
        </div>


        <div class="bg-yellow-700">
          <div class="m-auto w-fit">
            <h3 class="text-2xl uppercase">Catering</h3>
          </div>
        </div>

        <div 
          class="relative bg-fixed bg-cover bg-center bg-no-repeat z-0" 
          style="background-image:url('/charcuterie.jpg')"
          >
          <svg viewBox="0 0 100 100" preserveAspectRatio="none" class="w-full h-16 fill-current text-black border-none drop-shadow-lg" >
            <polygon class="fill-yellow-700" points="0,0 100,0 50,65" />
          </svg>

          <div class="
                flex flex-col md:flex-row 
                justify-center items-center md:items-start
                py-6 my-6
                bg-black bg-opacity-50 
                border-x-0 border-double border-2 border-yellow-500
                text-white font-semibold text-justify
            ">
            <div class="flex flex-col justify-center w-1/2 md:mr-12 pb-6 md:pb-0 ">
              We offer onsite cooking for your parties, weddings, and events. Our menu is diverse and can fit any dietary needs. If you are interested in having us come cook for you and your guests, please contact us.
            </div>
          </div>
          <svg viewBox="0 0 100 100" preserveAspectRatio="none" class="w-full h-12 fill-current text-black" >
            <polygon class="fill-gray-900" points="0,100 100,100 100,0 50,45 0,0" />
          </svg>
        </div>
        
        <svg viewBox="0 0 100 100" preserveAspectRatio="none" class="w-full h-16 fill-current text-black border-none drop-shadow-lg" >
          <polygon class="fill-gray-900" points="0,0 100,0 50,65" />
        </svg>

        <div class="h-32"></div>

        <svg viewBox="0 0 100 100" 
          preserveAspectRatio="none" 
          class="w-full h-16 fill-current text-black border-none" >
          <polygon 
            class="fill-gray-900"
            points="0,100 100,100 50,0" 
          />
        </svg>

        <svg 
          viewBox="0 0 100 100" 
          preserveAspectRatio="none" 
          class="bg-gray-900 w-full h-16 fill-current text-black border-none" >
          <polygon 
            class="fill-black"
            points="0,100 100,100 50,0" 
          />
        </svg>

        <div class="bg-black pb-4">
          <div class="flex justify-center">
            <a href="https://instagram.com/pepespaella" target="_blank">
              <Instagram width="64px" height="64px" />
            </a>

            <a href="https://www.facebook.com/pepespaella" target="_blank">
              <Facebook width="64px" height="64px" />
            </a>
          </div>
          <div class="flex justify-center">
            <span class="text-white block">jay@pepespaella.com</span>
          </div>
        </div>
      </div>
    </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage',
  // props: {
  //   highlight: String
  // },
  created(){
    this.$nuxt.$on('new-highlight', ($e : any) => this.highlight = $e)
  },
  data() {
    return {
      highlight: 'fill-current'
    }
  }
})
</script>

<style>
  @tailwind base;
  @tailwind components;
  @tailwind utilities;

  html {
    background-color: black;
  }
  h2{
    font-family: theme('fontFamily.mono');
    font-size: theme('fontSize.3xl');
  }
</style>