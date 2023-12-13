<template>
    <div class="block">
        Click me
    </div>
</template>

<script>
    export default {
        name: 'BlockComp',
        props:['delay']
    }
</script>

<style scoped>
.block{
    width: 400px;
    border-radius: 20px;
    background: #c921b0;
    color: white;
    text-align: center;
    padding: 100px 0;
    margin: 40px auto;
}

</style>