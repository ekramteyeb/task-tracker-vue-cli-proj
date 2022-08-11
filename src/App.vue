<template >
   <div class="container">
      <Header title="Task-tracker" />
   </div>
</template>

<script>
  import Header from './components/Header'

export default {
  name: 'App',
  components: {
    Header,
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
.btn {
  padding:0.6rem 1.5rem;
  color:white;
  font-size:16px;
  font-weight: bold;
  border-radius: 0.2rem;
  border:none;
  margin:1rem;
}
</style>
