<template>
  <header class="header">
    <router-link to="/" class="header__home">
      <img src="https://mospolytech.ru/local/templates/main/dist/img/logos/mospolytech-logo-white.png" alt="" class="header__img" />
    </router-link>
    <nav class="header__nav">
      <router-link class="header__link" to="/">Главная</router-link>
      <router-link class="header__link" to="/news">Новости</router-link>
    </nav>
  </header>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.header {
  display: flex;
  padding: 10px 30px  ;
  align-items: center;
  text-align: center;
  background: #00aeff;
  &__img {
    width: 48px;
    height: 48px;
    text-align: left;
  }
  &__nav {
    width: 150px;
    display: flex;
    justify-content: space-between;
  }
  &__link{
    text-decoration: none;
    color: #000;
    text-align: center;
  }
}
</style>
