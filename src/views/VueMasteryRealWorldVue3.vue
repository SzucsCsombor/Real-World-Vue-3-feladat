<script setup lang="ts"></script>

<template>
  <div id="app">
    <h4>Vue Mastery - Real Wolrd Vue 3 example</h4>
    <div id="nav">
      <router-link :to="{ name: 'EventList' }">Events</router-link> |
      <router-link :to="{ name: 'AboutComp' }">AboutComp</router-link>
    </div>
    <router-view />
  </div>
</template>

<style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
  }

  #nav {
    padding: 30px;
  }

  #nav a {
    font-weight: bold;
    color: #2c3e50;
  }

  #nav a.router-link-exact-active {
    color: #42b983;
  }
</style>
