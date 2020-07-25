<template>
  <div class="text-yellow-400 bg-blue-600 h-screen">
    {{ thing }}
  </div>
</template>

<script>
export default {
  setup() {
    const thing = process.env.VUE_APP_TEST_THING;
    return {
      thing
    };
  }
};
</script>
