<template>
  <div id="app">
    <nav class="navbar navbar-expand navbar-dark bg-dark">
      <router-link to="/" class="navbar-brand px-4">Demo</router-link>
      <div class="navbar-nav mr-auto">
        <li class="nav-item">
          <router-link to="/add" class="nav-link">Add user</router-link>
        </li>
      </div>
    </nav>
    <div class="container mt-4">
      <router-view />
    </div>
  </div>
</template>
<script>
export default {
  name: "app"
};
</script>
