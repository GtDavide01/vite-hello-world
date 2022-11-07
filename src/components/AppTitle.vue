<script>
    export default{
        data(){
            return{
                titleUser: "La mia prima app con Vite",
            }
        }
    }

</script>

<template>
    <h1>{{titleUser}}</h1>
</template>


<style scoped >
 h1{
    font-size: 3rem;
    font-style: oblique;
    text-align: center;
 }
</style>