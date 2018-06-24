<template>
<div class="header" :style="{background: bgColor}">
    <span class="home" :style="{background: bgColor}">首页</span>
    <h2 class="title"><slot name="title"></slot></h2>
</div>
</template>
<script>
export default {
    props: ['bgColor']
}
</script>
<style scoped>
.header{
    height: 1rem;
    /* background-color: rgb(33, 150, 243); */
    line-height: 1rem;
    color: #ffffff;
    position: fixed;
    top: 0;
    width: 100%;
}
.title{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
}
.home{
    color:#ffffff;
    /* background-color:rgb(33, 150, 243);  */
    margin-left: .1rem;
}
</style>
