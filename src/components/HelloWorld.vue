<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="greetings">
    <h1 class="green">官网发布页</h1>
    <h2>(注意官网变动)</h2>
    <h3>● 如以下网址有某个无法打开，请留言给客服，谢谢</h3>
    <h3>● 打开官网前，请先断开你的 FQ（VPN）软件</h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
