<script setup>
import TheHeader from "@/components/TheHeader.vue";
import TheFooter from "./components/TheFooter.vue";
import TheSection from "./components/TheSection.vue";
import TheContent from "./components/TheContent.vue";
import { reactive } from "@vue/reactivity";
</script>

<template>
  <header>
    <TheHeader header="header.text" message="message" />
  </header>
  <main>
    <TheSection />
    <TheContent />
  </main>

  <footer class="text-muted py-5">
    <TheFooter />
  </footer>
</template>

<style></style>
