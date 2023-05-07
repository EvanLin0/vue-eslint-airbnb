<template>
  <div class="hello">
    <h1>首页</h1>
    <button @click="handleClick">点击</button>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
  methods:{
    handleClick(){
      console.log("-----")
    }
  }
};
</script>
