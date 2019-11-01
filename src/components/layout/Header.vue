<template>
  <header class="header">
    <h1>TodoLists</h1>
    <div id="nav">
      <router-link to="/" class="nav">
        Home
      </router-link> |
      <router-link to="/about" class="nav">
        About
      </router-link>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>
  .header {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
  }
  .header a {
    color: #fff;
    padding-right: 5px;
    text-decoration: none;
  }

  .nav {
    color: white !important
  }
  
</style>