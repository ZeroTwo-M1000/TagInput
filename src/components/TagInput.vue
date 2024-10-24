<script setup>
import { ref } from "vue"

const tags = ref(["Vue", "Nuxt", "Pinia"])
</script>

<template>
    <div class="tag-input">
        <div v-for="tag in tags" :key="tag" class="tag-input__tag">
            <span></span>
            <p>{{ tag }}</p>
        </div>
        <input type="text" placeholder="Add a tag" class="tag-input__text" maxlength="20" />
    </div>
</template>

<style lang="scss" scoped>
.tag-input {
    @apply flex w-full flex-wrap space-x-2 rounded-xl border p-3;

    &__tag {
        @apply my-1 flex items-center space-x-1 rounded-full border bg-gray-100 px-3 py-1;

        span {
            @apply h-3.5 w-3.5 cursor-pointer rounded-full bg-gray-300 text-white transition-all duration-300 ease-in-out hover:scale-110;
        }
    }
    &__text {
        @apply rounded outline-none;
    }
}
</style>
