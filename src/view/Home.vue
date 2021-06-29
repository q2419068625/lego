<template>
  <div class="home-container">
    <a-layout :style="{background: '#fff', height: '100%'}">
      <a-layout-header class="header">
        <div class="page-title">慕课乐高</div>
      </a-layout-header>
      <a-layout-content>
        <div class="list">
          <template-list />
        </div>
      </a-layout-content>
      <a-layout-footer>
        版权
      </a-layout-footer>
    </a-layout>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import TemplateList from "../components/TemplateList.vue"
export default defineComponent({
  components: { TemplateList },
  setup() {
    console.log(123);
  }
});
</script>

<style>
.home-container {
  height:100%;
  width: 100%;
}
.home-container .header {
  background-color:rgba(0,0,0,.5);
}
.page-title {
  color: #fff;
  font-size: 30px;
}
.list {
  margin-top:30px;
}
</style>
