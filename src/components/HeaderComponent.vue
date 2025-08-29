<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
  <header>
    <nav>
      <ul>
        <li class="atual">
          <router-link to="/">Home</router-link>
        </li>
        <li>
          <router-link to="/about">About</router-link>
        </li>
        <li>
          <router-link to="/projects">Projects</router-link>
        </li>
        <li>
          <router-link to="/connect">Connect</router-link>
        </li>
      </ul>
    </nav>
  </header>
</template>

<style scoped>
header {
  padding: 5vw 10vw;
  font-size: 0.8rem;

  & ul {
    display: flex;
    width: fit-content;
    margin: 0 auto;
    background: rgba(255, 255, 255, 0.5);
    padding: 5px;
    border-radius: 50px;
    border: 1px solid rgb(211, 211, 211);

    & li {
      padding: 8px 15px;
    }

    & .router-link-active {
      background-color: black;
      color: white;
      padding: 5px 10px;
      border-radius: 30px;
    }
  }
}
</style>
