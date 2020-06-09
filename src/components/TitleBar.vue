<template>
    <div class="title-bar">
        <div class="tittle-bar-button">1</div>
        <div class="tittle-bar-button">2</div>
        <div class="tittle-bar-button">3</div>
    </div>
</template>

<script>
    export default {
        name: "TitleBar"
    }
</script>


<style scoped>

    .title-bar{
        background-color: pink;
        height: 30px;
    }
    .tittle-bar-button{
        float: right;
        height: 15px;
        width: 15px;
        border: 1px solid black;
        background-color: red;
        margin: 5px 5px;
    }


</style>