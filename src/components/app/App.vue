
<template>
  <div id="app">
    <b-nav >
      <b-nav-item v-for="bunda in bundas" class="comunista">
        {{ bunda.title }}
      </b-nav-item>
    </b-nav>
  </div>
</template>

<script src="./App.js"></script>
<style>
  @import './App.css';
</style>