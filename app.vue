<template>
  <div>
    <Navbar />
    <NuxtPage></NuxtPage>
  </div>
</template>
<script>
import Navbar from '~/components/Navbar.vue';

export default {
  components: {
    Navbar,
  },
};
</script>