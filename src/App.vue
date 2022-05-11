<script setup>
import Tabs from './components/Tabs.vue'
import Tab from './components/Tab.vue'
</script>

<template>
  <Tabs>
    <Tab title='Tab One'>Lorem ipsum dolor sit, amet. 1</Tab>
    <Tab title='Tab Two'>Lorem ipsum dolor sit, amet. 2</Tab>
    <Tab title='Tab Three'>Lorem ipsum dolor sit, amet. 3</Tab>
    <Tab title='Tab Four'>Lorem ipsum dolor sit, amet. 4</Tab>
    <Tab title='Tab Five'>Lorem ipsum dolor sit, amet. 5</Tab>
  </Tabs>
</template>

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
