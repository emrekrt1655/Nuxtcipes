<script setup lang="ts">

</script>

<template>
    <header class="py-4 border-b">
        <nav class="flex container items-center">
            <NuxtLink to="/" class="flex gap-1 items-center">
                <NuxtImg densities="x1" width="50px" format="webp" src="/icon-green.png" alt="green-icon"/>
                <span class="text-3xl font-bold">Nuxtcipes</span>
            </NuxtLink>
            <ul class="flex gap-6 ml-auto text-xl font-bold capitalize ">
                <li>
                    <NuxtLink to="/">Home</NuxtLink>
                </li>
                <li>
                    <NuxtLink to="/About">About</NuxtLink>
                </li>
            </ul>
        </nav>
    </header>
</template>


<style scoped></style>