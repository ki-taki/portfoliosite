<script setup lang="ts">
useHead({
    titleTemplate: (title) => {
        return title ? ` T - ${title}` : ' T';
    },
})
</script>

<template>
    <Header />
    <slot></slot>
    <Footer />
    <Background />
</template>