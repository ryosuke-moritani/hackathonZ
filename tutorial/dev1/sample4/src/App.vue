<script setup>
const handleClick = () => {
  alert("ボタンがクリックされました")
}

const handleMouseOver = () => {
  alert("マウスが乗った")
}
</script>

<template>
  <h1>Sample4</h1>
  <button @click="handleClick">click</button>
  <button @mouseover="handleMouseOver">mouseover</button>
</template>




