<script setup lang="ts">
import { RiHome2Line } from '@remixicon/vue'
</script>

<template>
    <header class="bg-[#212c38] py-3 justify-center flex gap-8 text-white">
        <button class="flex items-center gap-1">
            <RiHome2Line size="15px" />
            <p>Home</p>
        </button>
        <NuxtImg src="/mi-logo.png" width="30" height="30" />
        <p>a</p>
    </header>
</template>
