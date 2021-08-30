<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <Form />
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
import Form from './components/form.vue'

export default {
  name: 'App',
  components: {
    Form,
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

* {
    margin: 0;
}

.form-title {
    padding: 15px;
    font-size: 25px;
}

.form {
    margin: auto;
    padding: 20px;
    width: 400px;
    height: 500px;
    background-color: rgb(56, 164, 207);
    display: flex;
    flex-direction: column;
    border: rgb(158, 158, 158) 2px solid;
}

.error-message {
  color: rgb(201, 11, 11);
  font-weight: 600;
  font-size: 20px;
}

.form div {
    padding-left: 110px;
    padding-bottom: 7px;
    text-align: left;
}

.form div label {
    font-weight: 600;
}

.form div input {
    padding: 5px;
}

.address-content {
  display: flex;
  /* flex-direction: column; */
}

.address-content div { 
  padding-left: 0px;
  padding-right: 20px;
}

.address-content div p { 
  font-size: 13px;
  font-weight: 600;
}

</style>
