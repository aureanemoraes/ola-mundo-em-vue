<template>
    <h1>Olá, Mundo!</h1>
    <h2>Primeiro projeto em vue 3 \o/</h2>
</template>

<script lang="ts">
    import { defineComponent } from 'vue';

    export default defineComponent({
        name: "OlaMundo"
    });
</script>

<style>
    h1 {
        color: green;
    }

    h2 {
        color: blue;
    }
</style>