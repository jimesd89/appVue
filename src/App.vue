<template>
  <TheHeader title="The world"></TheHeader>
  <TheResources></TheResources>
</template>

<script>

import TheHeader from './components/layouts/TheHeader.vue';
import TheResources from './components/learning-resource/TheResources.vue';

export default {
  components: {
    TheHeader,
    TheResources
  },
  
};
</script>
