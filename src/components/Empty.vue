<template>
  <div>
    <!-- <img src="/assets/images/icons/empty.svg" alt="Empty Box" /> -->
    <p class="text-light text-center">{{ msg }}</p>
  </div>
</template>

<script>
export default {
  props: {
    msg: String,
  },
}
</script>

<style scoped>
img {
  height: 100px !important;
  width: 100px !important;
}
</style>
