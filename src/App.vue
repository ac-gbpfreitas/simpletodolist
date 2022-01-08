<template>
  <FormTodoList/>
</template>

<script>
  import FormTodoList from './components/FormTodoList.vue';
  
  export default {
    name: 'App',
    components: {
      FormTodoList
    },
  }
  
</script>

<style>
  body {
    font-family: sans-serif;
    padding-top: 1em;
    padding-bottom: 1em;
    font-size: 2em;
    width: 80%;
    margin: 0 auto;
  }
</style>