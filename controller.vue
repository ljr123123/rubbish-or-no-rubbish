<template>
    <div class="controller">
        <div class="move"></div>
        <img src="../assets/up.svg" class="move"/>
        <div class="move"></div>
        <img src="../assets/left.svg" class="move"/>
        <div class="move"></div>
        <img src="../assets/right.svg" class="move"/>
        <div class="move"></div>
        <img src="../assets/down.svg" class="move"/>
        <div class="move"></div>
    </div>
</template>
<script setup>
</script>
<style scoped>
.controller{
    height:200px;
    width:200px;
    margin:20px;
    display: flex;
    flex-wrap: wrap;
}
.move{
    height:33%;
    width:33%;
}

</style>