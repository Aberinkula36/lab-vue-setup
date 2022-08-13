<template>
  <h1>{{ msg }}</h1>
</template>

<script>
export default {
  name: 'ToDoItem',
  data() {
    return {
      msg: 'Este es el nuevo componente de Pepe',
    };
  },
};
</script>

<style scoped>
h1 {
  color: green;
  margin: 40px 0 0;
}
</style>
