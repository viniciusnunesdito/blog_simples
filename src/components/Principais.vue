<template>
    <div id="principais">
        <img src="img/principal1.jpeg" alt="">
        <img src="img/principal2.png" alt="">
        <img src="img/principal3.png" alt="">
    </div>
</template>

<script>
export default {
    name: "Principais"
}
</script>

<style scoped>
#principais {
    padding: 10px;
    width: 50%;
}

img {
    height: 20%;
    display: flex;
    justify-content: flex-end;
    align-items: center;
}
</style>