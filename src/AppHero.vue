<script>
export default {
    data() {
        return {
            picture: "https://picsum.photos/600/300",
        }
    },
    // methods: {
    //     getImageURL() {
    //         const realUrl = new URL(this.picture, import.meta.url);
    //         return realUrl.href
    //     }
    // }
}
</script>

<template>
    <img src="https://picsum.photos/600/300" alt="picsum">
</template>

<style scoped>
img {
    border-radius: 15px;
}
</style>

