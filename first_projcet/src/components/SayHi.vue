<template>
    <div class="hi">
      <input type='button' @click="show_my_value()" value="..."/>
    </div>
  <div v-if="a>1"></div>
</template>

<script>
  export default {
    data() {
      return {
        my_value: '你好，vue！本消息来自于变量'
      }
    },
    methods: {
      show_my_value: function () {
        alert('my_value:' + this.my_value);
      }
    }
  }
</script>

<style scoped>
</style>
