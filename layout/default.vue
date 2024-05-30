import { NuxtLink } from '../.nuxt/components';
<template>
  <nav>
    <NuxtLink to="/">Home</NuxtLink>
  </nav>
  <main>
    <slot></slot>
  </main>
</template>

<script setup lang="ts"></script>

<style scoped></style>
