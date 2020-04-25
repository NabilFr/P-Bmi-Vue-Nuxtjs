<template>
  <div class="min-h-screen font-sans bg-gray-900 text-white pb-8">
    <navbar />
    <gender />
    <height />
    <ageWeight />
    <nuxt />
  </div>
</template>

<script>
import navbar from "~/components/common/navbar";
export default {
  components: {
    navbar
  }
};
</script>
