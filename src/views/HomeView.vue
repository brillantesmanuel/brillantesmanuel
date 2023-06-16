<script setup lang="ts">
import Navigation from '@/components/navigation.vue';
import About from '@/views/AboutView.vue';
import Projects from '@/views/ProjectsView.vue';
import Contact from '@/views/ContactView.vue';
</script>

<template>
    <main>
        <h1><span>Full Stack</span> <span>Web Developer.</span></h1>
        
        <about />

        <projects />

        <contact />
    </main>
</template>
