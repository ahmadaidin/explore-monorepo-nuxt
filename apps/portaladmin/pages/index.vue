<template>
  <div>
    <NuxtTutorial />
    <HelloWorld />
  </div>
</template>

<script lang="ts">
import Vue from 'vue';
import { HelloWorld } from '@civitas-lms/shared';
export default Vue.extend({
  name: 'HomeAdmin',
  components: {
    HelloWorld,
  },
});
</script>
