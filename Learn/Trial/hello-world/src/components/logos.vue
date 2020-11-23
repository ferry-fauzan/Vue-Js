<template>
<div class="logoWrap">
    <p>Find your best potential work</p>
    <p>{{nama}}</p>
</div>
</template>

<script>
export default {
    name: 'Logos',
    props:["nama"]
}
</script>

<style scoped>
.logoWrap{
    width :50%;
    overflow :hidden;
    margin :auto;
    background: rgb(45, 187, 163);
}
</style>