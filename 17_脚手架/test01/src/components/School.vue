<template>
  <div class="demo">
    <!-- 组件的结构 -->
    <h2>学校名称:{{name}}</h2>
    <h2>学校名称:{{address}}</h2>
    <button @click="showName">显示信息</button>
  </div>
</template>

<script>
//组件交互相关代码
  export default{
    name:'School',
    data () {
      return {
        name: '张三',
        age: 18
      }
    },
    methods: {
      showName(){
        alert(this.name)
      }
    },
  }
    
</script>

<style>
.demo{
  background-color: skyblue;
}
</style>