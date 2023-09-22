<template>
  <div id="app">
    <router-view />
    <FooterVue />
  </div>
</template>

<script>
import FooterVue from "@/components/FooterVue.vue";

export default {
  components: {
    FooterVue,
  },
};
</script>