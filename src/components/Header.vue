<template>
  <header class="header">
    <h1>MY TODO LIST</h1>
    <div id="nav">
      <!-- <router-link to="/">Home</router-link> | -->
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header',
};
</script>

<style scoped>
  .header {
    background: rgb(104, 97, 97);
    color: #fff;
    text-align: center;
    padding: 10px;
  }
  .header a {
    color: #fff;
    padding-right: 5px;
    text-decoration: none;
  }
</style>
