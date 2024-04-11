<template>
  <div class="navigation">
    <div class="flex link">
      <img class="h-[30px] w-[30px] rounded-[30px] mr-[10px]" src="/4.jpg" alt=""/> 
      <nuxt-link to="/" > Домой</nuxt-link>
    </div>
    <div class="mr-[50px]">

      <nuxt-link to="/about_us" class="link">О компании</nuxt-link>

      <nuxt-link to="product" class="link">Продукты</nuxt-link>

      <nuxt-link to="settings" class="link">Обучение</nuxt-link>
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
  border-radius: 20px;
  padding: 5px 10px 5px 10px;
  border-color: black;
  background-color:aqua
}


</style>
