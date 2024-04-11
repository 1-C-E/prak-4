<template>
  <div class="navigation">
    <nuxt-link to="/" class="link"> домой</nuxt-link>
    <div class="container">

      <nuxt-link to="/about_us" class="link">о нас</nuxt-link>

      <nuxt-link to="product" class="link">продукты</nuxt-link>

      <nuxt-link to="settings" class="link">настройки</nuxt-link>
    </div>
  </div>

</template>

<style>
.navigation {
  display: flex;
  justify-content: space-between;
  margin-top: 50px;
}

.link {
  border-width: 2px;
  margin-left: 50px;
}

.container {

}
</style>
