<template>
  <header>
    <h1>My Site</h1>
    <nav>
      <ul>
        <li><nuxt-link to="/">Home</nuxt-link></li>
        <li><nuxt-link to="/about">About</nuxt-link></li>
      </ul>
    </nav>
  </header>
</template>

<script lang="ts">
export default {
  name: 'SiteHeader'
}
</script>

