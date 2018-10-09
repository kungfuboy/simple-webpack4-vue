<template>
    <div class="main">
        <div>父组件是 蓝色</div>
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
  color: blue;
}
</style>