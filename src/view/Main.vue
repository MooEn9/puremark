<template>
    <div class="main">
        <title-bar></title-bar>
    </div>
</template>

<script>
    import TitleBar from "../components/TitleBar";
    export default {
        name: "Main",
        components: {TitleBar}
    }
</script>

<style scoped>

    .main{
        height: 100vh;
    }

</style>