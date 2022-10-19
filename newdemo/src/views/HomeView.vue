<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <button @click="isClick">
      2222
    </button>
  </div>
</template>

<script setup>
// @ is an alias to /src
const isClick = () => {
  alert('222222')
}
</script>
