<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Demo/>
    <m-card imgSrc="java.png" summary="我不信"/>
    <m-card imgSrc="c语言.png" summary="学c语言">
      <template v-slot:footer>
        <div>我是c语言的页脚</div>
      </template>
    </m-card>
    <m-card imgSrc="springboot.png"  :width="370" :imgHeight="90">
      你品你细品
    </m-card>
  </div>
</template>

<script>

export default {
  name: 'App',
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
