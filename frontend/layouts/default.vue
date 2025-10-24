<template>
    <div>
        <nav class="flex flex-row justify-between h-10 my-4 mx-[2%] items-center">
            <router-link to="/"><NuxtImg src="/logo.avif" alt="logo" class="size-20 object-cover"/></router-link>
            <div class="flex flex-row gap-2">
                <router-link to="/login" class="button1 px-10 h-fit py-1">Log In</router-link>
                <router-link class="button2 px-6 h-fit py-1"  to="/pricing">Pricing</router-link>
            </div>
        </nav>

        <main class="mx-[10%] my-[10%]">
            <slot></slot>
        </main>

        <footer class="h-fit py-4 flex flex-col items-start">
            <div class="flex flex-row items-center">
                <router-link to="/"><NuxtImg src="/logo.avif" alt="logo" class="size-32 object-cover"/></router-link>
                <h1 class="h1">OmniPost</h1>
            </div>
            <div class="flex flex-row gap-4 items-center ml-8">
                <icon name="ic:baseline-tiktok" class="icon text-black" />
                <icon name="mdi:instagram" class="hover:text-amber-600 icon text-black"/>
                <icon name="mdi:youtube" class="hover:text-red-500 icon text-black" />
            </div>
            <p class="p ml-8 my-4">@OmniPost</p>
        </footer>
    </div>
</template>

<script setup lang="ts">

</script>
