<template>
  <n-layout id="app">
    <n-layout-header>
      <n-tabs type="line" animated justify-content="center" size="large">
        <n-tab name="oasis" tab="Oasis"> Wonderwall </n-tab>
        <n-tab name="the beatles" tab="the Beatles"> Hey Jude </n-tab>
        <n-tab name="jay chou" tab="周杰伦"> 七里香 </n-tab>
      </n-tabs>
    </n-layout-header>
    <n-layout has-sider>
      <n-layout-sider content-style="padding: 24px;"> 海淀桥 </n-layout-sider>
      <n-layout-content content-style="padding: 24px;">
        <router-view />
      </n-layout-content>
    </n-layout>
  </n-layout>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "MainNav",
});
</script>
