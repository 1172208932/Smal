<template>
    <div>
        <CommonHeader bgColor="rgb(121, 85, 72)"><span slot="title">Book</span></CommonHeader>
        <h1>book</h1>
        <CommonFooter bgColor="rgb(121, 85, 72)"></CommonFooter>
    </div>
</template>
<script>
import CommonHeader from "@/components/common/Header";
import CommonFooter from "@/components/common/Footer";
export default {
    components:{
        CommonHeader,
        CommonFooter
    }
};
</script>
<style scoped>

</style>
