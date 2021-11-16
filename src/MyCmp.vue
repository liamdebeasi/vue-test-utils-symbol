<template>
  Hello World! myProp value: {{$props.myProp}}
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  props: {
    myProp: {
      default: Symbol()
    }
  }
});
</script>