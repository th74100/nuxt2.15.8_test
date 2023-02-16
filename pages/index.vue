<template>
    <main id="main">
        <h1 class="title">{{msg}}</h1>
    </main>
</template>
<script>
export default {
    name: 'index',
    data() {
        return {
            msg: 'this is test'
        }
    }
}
</script>
<style scoped>
    @import "@/static/css/index.css";
</style>