<template>
  <div>
    <div class="flex items-center justify-center mt-4">
      <img class="h-24" src="../assets/xplat-logo.png" alt="xPlat Logo" />
      <img class="h-24 ml-4" src="../assets/vue-logo.png" alt="xPlat Logo" />
    </div>

    <h1 class="text-4xl text-center text-green-500 mt-4">
      Welcome to xPlat - Vue
    </h1>

    <FeatureList />
  </div>
</template>

<script>
import FeatureList from "@/components/FeatureList";

export default {
  components: {
    FeatureList
  }
};
</script>

<style></style>
