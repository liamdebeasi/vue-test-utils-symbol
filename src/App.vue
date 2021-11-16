<template>
  <div>
    <MyCmp></MyCmp>
    
    <br />
    
    <MyCmp myProp="ABC"></MyCmp>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import MyCmp from '@/MyCmp.vue';

export default defineComponent({
  name: 'Home',
  components: {
    MyCmp
  }
});
</script>