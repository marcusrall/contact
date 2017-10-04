<template lang="html">
  <nav class="navbar" role="navigation" aria-label="main navigation">
    <div class="navbar-brand">
      <a class="navbar-item" href="http://bulma.io">
        <img src="" alt="PHOTOBOOK" width="112" height="28">
      </a>
      <div class="navbar-menu is-active">
        <router-link class="navbar-item" to="/home">Home</router-link>
        <router-link class="navbar-item" to="/about">About</router-link>
      </div>

      <button class="button navbar-burger">
        <span></span>
        <span></span>
        <span></span>
      </button>
    </div>
</nav>
</template>

<script>
export default {
}
</script>

<style lang="css">
</style>
