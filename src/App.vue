<template>
 <formInput />
</template>

<script>
import formInput from './components/formInput.vue' 
export default {
   name: 'App',
    components: { formInput }
}
</script>

<style>
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
  margin-top: 60px;
}
body {
  margin: 0;
  background-image: url('./assets/bg3.jpg');
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  background-attachment: fixed;
}
</style>
