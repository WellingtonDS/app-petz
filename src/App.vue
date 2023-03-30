<template>
  <main id="app">
    <Header />
    <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </nav>
    <router-view />
    <Footer />
  </main>
</template>

<script>
import App from './App';
export default App
</script>

<style lang="scss" >
@import './App.scss';
</style>
