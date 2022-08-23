<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/foto-cv.jpeg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="Farhan Rian Hidayat" />

      <nav>
        <RouterLink to="/">Personal</RouterLink>
        <RouterLink to="/skill">Skill</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style scoped>
header {
  line-height: 1.5;
  max-height: 100vh;
  margin-bottom: 40px;
  /* background-color: #E8F9FD; */
  /* margin: 50px; */
}

.logo {

  display: block;
  margin: 0 auto 2rem;
  border-radius: 50%;
}

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 1rem;
}

nav a.router-link-exact-active {
  color: var(--color-text);
  border-radius: 15px;
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
  border-radius: 15px;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 1rem;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    /* padding: 1rem 0; */
    margin-top: 1rem;
  }
}
</style>
