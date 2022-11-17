<template>
    <div class="">
      <div 
        class="w-full relative bg-fixed bg-cover" 
        style="background-image: url('/banner5.jpg')"
        >
        
        <Header />
        
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
              We strive to provide a unique culinary experience in fantastic locations and settings. You may have tried our paella at music festivals, your farmer's market, a wedding, or any number of other events, either way we look forward to working with you. 
            </div>
          </div>
          
          <svg viewBox="0 0 100 100" preserveAspectRatio="none" class="w-full h-8 text-black border-none" >
            <polygon class="fill-red-600" points="0,100 100,100 50,50" />
          </svg>
          <div class="bg-red-600 uppercase">
            <div class="m-auto w-fit">
             <h3 class="text-2xl">2023 Schedule Upcoming...</h3>
            </div>
          </div>
          <svg viewBox="0 0 100 100" preserveAspectRatio="none" class="w-full h-8 text-black border-none bg-red-600" >
            <polygon class="fill-sky-500" points="0,100 100,100 100,0 50,45 0,0" />
          </svg>
        </div>

        <div class="bg-sky-500">
          <div class="m-auto w-fit">
            <h2 class="text-xl">PAST EVENTS</h2>
          </div>
        </div>
        
        <Event 
          startFillColor="fill-sky-500" 
          endFillColor="fill-yellow-600" 
          eventImage="/forest-fair-2022.jpg"
          eventTitle="Girdwood Forest Fair"
          eventDate="July 1st - 3rd 2022"
          eventLocation="Girdwood, AK"
          eventLink="https://girdwoodforestfair.com/"
          bgImage="background-image: linear-gradient(to bottom, rgba(0, 0, 0, 0.9), rgba(0,0,0, 0.1)), url('/forest-fair-cropped.jpg')"
          />

        <Event 
          startFillColor="fill-yellow-600" 
          endFillColor="fill-red-700" 
          eventImage="/salmonfest-poster-2022.jpg"
          eventTitle="Salmonfest"
          eventDate="August 5th - 7th 2022"
          eventLocation="Ninilchik, AK"
          eventLink="https://salmonfestalaska.org/"
          bgImage="background-image: linear-gradient(to bottom, rgba(0, 0, 0, 0.9), rgba(0,0,0, 0.1)), url('/salmonfest-2022.jpg'); background-position: center"
          />

        <Event 
          startFillColor="fill-yellow-600" 
          endFillColor="fill-red-700" 
          eventTitle="Spenard Jazzfest"
          eventDate="June 1st - 5th 2022"
          eventLocation="Spenard!"
          eventLink="https://www.spenardjazzfest.org/"
          bgImage="background-image: linear-gradient(to bottom, rgba(0, 0, 0, 0.9), rgba(0,0,0, 0.1)), url('/jazzfest.jpg'); background-position: center"
          />
          
        <Event 
          startFillColor="fill-red-700" 
          endFillColor="fill-yellow-700" 
          eventImage="/chickenstock-poster-2021.jpg"
          eventTitle="Chickenstock!"
          eventDate="June 3rd - 5th 2021"
          eventLocation="Chicken, AK"
          eventLink="https://www.facebook.com/ChickenstockMusicFest/"
          bgImage="background-image: linear-gradient(to bottom, rgba(0, 0, 0, 0.9), rgba(0,0,0, 0.1)), url('/chickenstock-2021.jpg'); background-position: center"
          />

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
  name: 'IndexPage'
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