<script>
    export default{
        data(){
            return{

            }
        },
        methods :{
            // metodo per immagini
            getImagePath(){
                return new URL(`../assets/img/ratchet-and-clank-rift-apart-keyart.jpg`, import.meta.url).href;
            }
        }
    }

</script>

<template>
    <section class="image-jumbotron">
        <img :src="getImagePath()" alt="">
    </section>
</template>


<style scoped >
.image-jumbotron {
    width: 100%;
    height: 50vh;
}
.image-jumbotron img {
    width: 100%;
    height: 100%;
    object-fit:contain;
}
</style>