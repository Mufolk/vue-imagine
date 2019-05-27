<template>
    <div id="TopHeader">
      <b-nav v-for="item in menuItens" v-bind:key="item.id">
        <b-nav-item class="navigation-item">
          <a v-bind:href="item.link" class="navigation-item">{{item.name}}</a>
        </b-nav-item>
      </b-nav>
    </div>
</template>

<script src="./TopHeader.js"></script>
<style>
  @import './TopHeader.css';
</style>
