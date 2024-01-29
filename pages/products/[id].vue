<template>
    <div>
        <h3>Product id is {{id}}</h3>
    </div>
</template>

<script setup>
    const {id} = useRoute().params
</script>

<style lang="scss" scoped>

</style>