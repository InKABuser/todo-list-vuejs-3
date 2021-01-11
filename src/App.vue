<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <Todo-list />
</template>

<script>

import TodoList from './components/Todo-list.vue'


export default {
  name: 'App',
  components: {
    TodoList,
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
    --bright-blue:#000220;
    --check-gradieant: linear-gradient(#57DDFF, #C058F3);
    --very-light-grey: #FAFAFA;
    --Very-Light-Grayish-Blue: #FFFFFF;
    --ight-grayish-blue: #D2D3DB;
    --dark-grayish-blue: #9394A5;
    --very-dark-grayish-blue: #484B6A;
    --heading: #ffffff;
    --border-color: #F5F5F8;

    --Very-Dark-Blue: #181824;
    --Very-Dark-Desaturated-Blue: #24273C;
    --Light-Grayish-Blue: #CACDE8;
    --Light-Grayish-Blue : #E4E5F1;
    --Dark-Grayish-Blue: #777A92;
    --Very-Dark-Grayish-Blue: #4D5066;
    --Very-Dark-Grayish-Blue: #393A4C;

    --blue-text: #1D86D5;
    --bg-mobile-light: url("~@/assets/bg-mobile-light.jpg");
    --bg-desktop-light: url("~@/assets/bg-desktop-light.jpg");
    --theme-icon-light: url("~@/assets/icon-moon.svg");
    --check-icon: url("~@/assets/icon-check.svg");
    --bg-mobile-dark: url("~@/assets/bg-mobile-dark.jpg");
    --bg-desktop-dark: url("~@/assets/bg-desktop-dark.jpg");
    --theme-icon-dark: url(" ~@/assets/icon-sun.svg"); 

}
</style>
