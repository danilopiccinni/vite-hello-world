<script>

export default {
        data() {
            return {
                image: "/img/01.webp",


                activeIndex : 0,
                
                
                }
        },

        methods : {

            scorriImmagini() {
                this.activeIndex++
            }
        },

    }

</script>

<template>

    <img :src="image" alt="">

</template>

<style>

    img {
        width: 80%;
    }

</style>