<script setup>

</script>
<template>
<div class="poems">
    <div class="card">
    <img class="background" src="../assets/imgs/fondo.jpg" alt="">
    <div class="text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos porro itaque nam. Harum, obcaecati? Libero quos at ab atque distinctio corporis? Dolorem vitae optio quia ipsam voluptatum odit necessitatibus eaque.</div>
    </div>
    <div class="card">
    <img class="background" src="../assets/imgs/fondo.jpg" alt="">
    <div class="text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos porro itaque nam. Harum, obcaecati? Libero quos at ab atque distinctio corporis? Dolorem vitae optio quia ipsam voluptatum odit necessitatibus eaque.</div>
    </div>
    <div class="card">
    <img class="background" src="../assets/imgs/fondo.jpg" alt="">
    <div class="text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos porro itaque nam. Harum, obcaecati? Libero quos at ab atque distinctio corporis? Dolorem vitae optio quia ipsam voluptatum odit necessitatibus eaque.</div>
    </div>
</div>
</template>
<style lang="scss" scoped>
@import "../assets/scss/Variables.scss";

.poems{
    display: flex;
    justify-content: space-around;
    align-items: center;
    margin-top: 2vw;
    margin-bottom: 2vw;
    
    .card{
        position: relative;
        display: inline-block;
        text-align: center;
        .background{
            width: 25vw;
            opacity: 50%;

        }
        .text{
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            color: white;
            font-family: Text;
        }
    }
}

</style>