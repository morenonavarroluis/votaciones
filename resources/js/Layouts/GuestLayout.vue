<script setup>
import ApplicationLogo from '@/Components/ApplicationLogo.vue';
import { Link } from '@inertiajs/vue3';
</script>

<template>
    <div
        class="flex min-h-screen flex-col items-center bg-gray-100 pt-6 sm:justify-center sm:pt-0"
    >
    
    <div
    class="mt-6 w-full overflow-hidden bg-white px-6 py-4 shadow-md sm:max-w-md sm:rounded-lg"
    >
    <div class="flex w-full justify-between items-center px-4 py-2">
        <h2 class="text-3xl font-extrabold tracking-tight text-gray-800">
            Votaciones
        </h2>

        <Link href="/">
            <ApplicationLogo class="h-16 w-16 fill-current text-indigo-600 transition-transform hover:scale-105" />
        </Link>
    </div>
  
  
            <slot />
        </div>
    </div>
</template>
