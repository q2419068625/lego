<template>
  <editor />
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import Home from './view/Home.vue'
import Editor from './view/Editor.vue'
export default defineComponent({
  name: 'App',
  components: {
    Editor
  }
});
</script>

<style>
#app {
  height:100%;
  width: 100%;
}
</style>
