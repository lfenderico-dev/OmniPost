<template>
    <div class="flex flex-col gap-16">
        <!-- Hero section -->
        <div class="h-fit">
            <div class="flex flex-col gap-2">
                <h1 class="h1 text-center">The AI content workspace that works for you.</h1>
                <p class="p text-center">Where your ideas, platforms, and AI come together to publish everywhere — faster and smarter.</p>
            </div>
            <div class="flex flex-col gap-2 my-6">
                <button class="button1">Get OmniPost</button>
                <button class="button2">Learn more</button>
            </div>
            <video class="hidden lg:block w-full" autoplay muted>
                <source src="">
            </video>
            <div class="flex flex-col gap-4">
                <p class="p text-center">Supported social media</p>
                <div class="grid grid-cols-3 gap-x-6 gap-y-2 items-center">
                    <NuxtImg src="/socialMedia/yt.avif" alt="youtube" class="size-18 object-cover"/>
                    <NuxtImg src="/socialMedia/tik tok.avif" alt="tik tok" class="size-18 object-cover"/>
                    <NuxtImg src="/socialMedia/ig.avif" alt="instagram" class="size-18 object-cover"/>
                    <NuxtImg src="/socialMedia/Linkedin.avif" alt="Linkedin" class="size-18 object-cover"/>
                    <NuxtImg src="/socialMedia/X.avif" alt="X" class="size-8 object-cover"/>
                </div>
            </div>
            
        </div>

        <!-- How does that work on mobile -->
        <div class="h-fit bg-blue-50 -mx-[12.5%] py-20 lg:hidden">
            <div class="flex flex-col gap-4 mx-[10%] text-center justify-center items-center">
                <div class="card">
                    <Icon name="hugeicons:quill-write-02" class="icon"/>
                    <h2 class="h2">You create your post once.</h2>
                </div>
                <icon name="mynaui:arrow-long-down" class="text-6xl"/>
                <div class="card">
                    <Icon name="mingcute:ai-fill" class="icon"/>
                    <h2 class="h2">AI adapts it to each platform.</h2>
                </div>
                <icon name="mynaui:arrow-long-down" class="text-6xl"/>
                <div class="card">
                    <Icon name="fluent:share-20-filled" class="icon"/>
                    <h2 class="h2">Automatically post or share everywhere.</h2>
                </div>
            </div>
        </div>

        <!-- How does that work on larger screens -->
        <div class="h-fit bg-blue-50 -mx-[12.5%] py-20 hidden lg:block">
            <div class="flex flex-row gap-4 mx-[10%] text-center justify-center items-center">
                <div class="card">
                    <Icon name="hugeicons:quill-write-02" class="icon"/>
                    <h2 class="h2">You create your post once.</h2>
                </div>
                <icon name="mynaui:arrow-long-right" class="text-9xl"/>
                <div class="card">
                    <Icon name="mingcute:ai-fill" class="icon"/>
                    <h2 class="h2">AI adapts it to each platform.</h2>
                </div>
                <icon name="mynaui:arrow-long-right" class="text-9xl"/>
                <div class="card">
                    <Icon name="fluent:share-20-filled" class="icon"/>
                    <h2 class="h2">Automatically post or share everywhere.</h2>
                </div>
            </div>
        </div>

        <!-- Features -->
        <div class="flex flex-col gap-10">
            <h1 class="h1 text-left">Let OmniPost take care of the boring part.</h1>
            <div class="flex flex-col gap-20">
                <div class="card shadow-black p-0">
                    <h2 class="h2 p-4 w-[70%]">You write once. Your agent adapts the post.</h2>
                    <video class="w-full" controls autoplay muted>
                        <source src="">
                    </video>
                    <div class="flex flex-col gap-1 p-4">
                        <p class="p font-bold opacity-100">Hands off your boringwork.</p>
                        <p class="p">What used to take hours in seconds. Tell it your idea and watch it work.</p>
                    </div>
                </div>
                <div class="card shadow-black p-0">
                    <h2 class="h2 p-4 w-[70%]">All analytics in a single place.</h2>
                    <video class="w-full" controls autoplay muted>
                        <source src="">
                    </video>
                    <div class="flex flex-col gap-1 p-4">
                        <p class="p font-bold opacity-100">Stop switching platforms to see how are you doing</p>
                        <p class="p">See how are you doing for all platform in one app.</p>
                    </div>
                </div>
                
            </div>
        </div>

        <!-- CTA -->
        <div>
            <h1 class="h1">Get it now.</h1>
            <NuxtImg src="/undraws/socialDashboard.avif" alt="social dashboard" class="w-full h-[50vh] my-4 object-cover"/>
            <div class="flex flex-col gap-2">
                <router-link to="/signup" class="button1 px-10 h-fit py-1 text-center">Sign Up</router-link>
                <router-link class="button2 px-6 h-fit py-1 text-center"  to="/pricing">Pricing</router-link>
            </div>
        </div>
    </div>
</template>

<script setup lang="ts">

</script>
