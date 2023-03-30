<script setup>
import Header from '../components/Header.vue';
import History from '../components/History.vue';
import Poetry from '../components/Poetry.vue';
import Footer from '../components/Footer.vue'
</script>

<template>
<body>  
<Header/>
<History/>
<Poetry/>
<Footer/>
</body>
</template>

<style lang="scss" scoped>
@import "../assets/scss/Variables.scss";

body{
    background-color: $Principal;

 
}


</style>