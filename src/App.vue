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

<style lang="scss">
html,
body {
  width: 100%;
  height: 100vh;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  width: 100%;
  height: 100%;
  overflow: hidden;
  background-color: #f1f0f5;
}

.n-tabs-tab-wrapper {
  padding: 0px 20px;
}
</style>
