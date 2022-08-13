<template>
<div>
    <button @click="HelloWorld()" id="button">Say Hi!</button>
</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    data: String,
    msg: String,
  },
  methods: {
    HelloWorld() {
      console.log('Hello World');
    },
  },
};
</script>

<style scoped>
    #button{
        background-color: blue;
        color: white;
        padding: 20px;
        border: none;
        border-radius: 20px;
    }
</style>
