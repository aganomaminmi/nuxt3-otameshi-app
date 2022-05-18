<template>
  <div style="height: 2000px">
    <h1>hello world!</h1>
  </div>
</template>

<script setup lang="ts">
onMounted(() => {
  if (process.client) {
    // window.addEventListener('scroll', () => {}, { passive: true })
    window.addEventListener('scroll', (e) => {
      // console.log(e.preventDefault())
      
      console.log('aaa', new Date().toString())
    }, { passive: true })
  }

})
</script>
