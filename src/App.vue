<script setup lang="ts">
import TagInput from "@/components/TagInput.vue"
</script>

<template>
    <div class="app">
        <h1>Vue Tag Input</h1>
        <TagInput />
    </div>
</template>

<style lang="scss" scoped>
.app {
    @apply flex flex-col items-start space-y-5 p-20;

    h1 {
        @apply text-5xl font-bold text-title;
    }
}
</style>
