<!-- //App.vue -->

<template>
  <div id="app" class="container">
    <h1>To-Do Application using Vue.js</h1>
    <!-- <MyTodoForm /> // using MyTodoForm component -->
    <MyTodoForm />
    <!-- <MyTodoList /> // using MyTodoList component -->
    <MyTodoList />

  </div>
</template>
<script>

import MyTodoList from './components/MyTodoList';
import MyTodoForm from './components/MyTodoForm';

export default {
  name: 'App',
  components: {
    MyTodoList, // renders the MyTodoList component
    MyTodoForm, // renders the MyTodoForm component
  },
};
</script>

<style>
.container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
</style>

<!-- <template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
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
</style> -->
