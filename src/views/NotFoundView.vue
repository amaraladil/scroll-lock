<template>
    <div class="not-found flex flex-col items-center justify-center h-screen">
        <h1 class="text-4xl font-bold mb-4">404 - Page Not Found</h1>
        <p class="text-lg">The page you are looking for does not exist.</p>
    </div>
</template>

<script>
export default {
    name: 'NotFoundView',
}
</script>

<style scoped>
.not-found {
    @apply text-center mt-20;
}
</style>