<script lang="ts" setup>
import TheWelcome from '../components/TheWelcome.vue'
</script>
<template>
    <main>
        <TheWelcome />
    </main>
</template>

<style>
.about {
    display: flex;
    align-items: center;
}
@media (min-width: 1024px) {
    .about {
        min-height: 100vh;
        display: flex;
        align-items: center;
    }
}
</style>
