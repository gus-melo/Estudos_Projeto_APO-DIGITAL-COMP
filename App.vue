<template>
  <Button buttonText="Clique Aqui" />
  <Input input-text label="Escreva" value="Escreva algo" />
  <Teste />
  <todolist />
</template>

<script>
import Button from './components/Button.vue';
import Input from './components/Input.vue';
import Teste from './components/Teste.vue';
import todolist from './components/todolist.vue';
export default {
  name: 'App',
  components: {
    Button,
    Input,
    Teste,
    todolist,
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>