<template>
  <div class="text-center mt-6">
    <div class="text-xl font-bold text-indigo-900">
      Features
    </div>

    <ul class="list-reset">
      <li
        v-for="feature in features"
        :key="feature"
        class="text-lg text-indigo-700 mt-2"
      >
        {{ feature }}
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      features: ["Vue CLI 3.x", "TailwindCSS"]
    };
  }
};
</script>
