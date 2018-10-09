<template>
    <div class="main">
        <div>这是父组件</div>
        <child />
    </div>
</template>
<script>
import Child from './child.vue'
export default {
  components: {
    Child
  }
}
</script>
<style lang='less'>
.main {
  color: #0000ff;
}
</style>