<template>
    <div 
        class="relative bg-fixed bg-cover bg-center bg-no-repeat" 
        :style="bgImage">
        <svg viewBox="0 0 100 100" preserveAspectRatio="none" class="w-full h-12 fill-current text-black" >
            <polygon :class="startFillColor" points="0,0 100,0 50,65" />
        </svg>

        <div class="flex pl-16 pb-16 flex-col md:flex-row justify-center m-auto w-80">
            <img v-if="eventImage" :src="eventImage" class="w-48 md:w-72" />
            <div class="md:pl-16 pt-8 text-white">
                <h2 class="text-xl md:text-4xl uppercase">{{ eventTitle }}</h2>
                <h3 class="">{{ eventDate }}</h3>
                <h3 class="">{{ eventLocation }}</h3>
                <div class="mt-4">
                    <a v-if="eventLink" :href="eventLink" target="_blank" class="rounded-md bg-red-800 p-2 hover:text-yellow-500">
                        !@~@!
                    </a>
                </div>
            </div>
        </div>

        <svg viewBox="0 0 100 100" preserveAspectRatio="none" class="w-full h-12 fill-current text-black" >
            <polygon :class="endFillColor" points="0,100 100,100 100,0 50,45 0,0" />
        </svg>
    </div>
</template>

<script>
export default {
    props: {
        startFillColor: String,
        endFillColor: String,
        bgImage: String,
        eventImage: String,
        eventTitle: String,
        eventDate: String,
        eventLocation: String,
        eventLink: String
    },
    setup() {
        
    },
}
</script>