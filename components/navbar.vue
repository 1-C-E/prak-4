<template>
  <div class="navigation">
    <nuxt-link to="/" class="link"> домоооооой</nuxt-link>
    <div class="container">

      <nuxt-link to="/about_us" class="link">онас</nuxt-link>

      <nuxt-link to="product" class="link">прукдты</nuxt-link>

      <nuxt-link to="settings" class="link">настойки</nuxt-link>
    </div>
  </div>

</template>

<style>
.navigation {
  display: flex;
  justify-content: space-between;
}
.link {
  border-width: 2px;
  margin-left: 50px;
}

.container {

}
</style>
