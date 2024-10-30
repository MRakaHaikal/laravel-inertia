<script setup>
defineProps({
        user: String
    })
</script>

<template>
    <Head title="About" />
    <h1 class="text-3xl font-bold">This is an About Page of {{ user }}</h1>
</template>
