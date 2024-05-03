<script>
export default{
    data() {
        return {
            title: "My banner title"
        }
    }
}
</script>

<template>
    <div class="banner">
        <h2>{{ title }}</h2>
        <img src="../assets/solar-flare.en.webp" alt="">

    </div>
</template>

<style>
.banner {
    position: relative;
}

.banner img {
    width: 100% ;
}

.banner h2{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    padding: 20px;
    background-color: rgba(0, 0, 0, 0.4);
    color: white;
}
</style>
