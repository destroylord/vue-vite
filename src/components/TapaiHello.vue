<script setup>
    import {ref} from 'vue'

    const msg = ref("Hello World!!")

</script>

<template>
    <div>
        <h1>{{msg}}</h1>
        <input v-model="msg">
    </div>
</template>

<style >

</style>

