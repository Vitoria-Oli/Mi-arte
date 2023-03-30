<script setup>

</script>

<template>

<header>
    <img class="logo" src="../assets/imgs/logo.png" alt="logo">

    <nav>
        <button class="btn">Home</button>
        <button class="btn">Obras</button>
        <button class="btn">Recomendaciones</button>
    </nav>
</header>

</template>

<style lang="scss" scoped>
@import "../assets/scss/Variables.scss";

header{
    background-color: $Details;
    height: 22%;
    display: flex;
    justify-content: space-between;
    align-items: center;

    .logo{
        width: 20vw;
        margin-left: 2vw;
    }

    nav{

        .btn{  
            background-color: transparent;
            border: none;
            margin-right: 2vw;
            height: 5vh;
            font-family: Titles;
            font-size: 2vw;
            color: white;

        }
    }
}

</style>