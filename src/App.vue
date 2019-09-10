<template>
  <div id="app">
    <nav class="nav nav-top bg-primary bg-gradient">
      <div class="nav-inner contained">
        <div class="nav-branding">
          <h1 class="nav-block banger mb-0">POW!</h1>
        </div>
        <div class="nav-content">
          <div class="ml-auto">
            <router-link class="nav-block" to="/#documentation"
              >Documentation</router-link
            >
            <router-link class="nav-block" to="/install-pow"
              >Installation</router-link
            >
          </div>
        </div>
      </div>
    </nav>
    <router-view></router-view>
  </div>
</template>

<style lang="scss">
@import "@/assets/scss/style";
</style>
