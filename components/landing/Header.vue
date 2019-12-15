<script>
  export default {
    name: "LandingHeader"
  }
</script>

<template>
  <header class="header">
    <div class="header__top">
      <div class="logo">
        <a class="logo__link" href="#">
          <img class="logo__img" src="~/assets/logo.svg" alt="">
          <span class="logo__name">Find-Psy</span>
        </a>
      </div>
      <nav class="menu header__menu">
        <ul class="menu__list">
          <li class="menu__item"><a class="menu__link" href="#">Публикации</a></li>
          <li class="menu__item"><a class="menu__link" href="#">Видео</a></li>
          <li class="menu__item"><a class="menu__link" href="#">Новости</a></li>
          <li class="menu__item"><a class="menu__link" href="#">События</a></li>
          <li class="menu__item"><a class="menu__link" href="#">Организации</a></li>
        </ul>
      </nav>
      <div class="settings header__settings">
        <div class="settings__language settings__language_rectangled">
          <span class="settings__name">Русский</span>
        </div>
        <div class="settings__city settings__city_rectangled">
          <span class="settings__name">Москва</span>
        </div>
      </div>
      <div class="user header__user">
        <div class="user__authentication user__authentication_rectangled">
          <span class="user__authorization">Войти</span>
        </div>
        <div class="user__authentication user__authentication_rectangled">
          <span class="user__registration">Регистрация</span>
        </div>
      </div>
<!--      <div class="header__mobile_menu">-->
<!--        <svg version="1.1" id="Capa_1" xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="124px" height="124px" viewBox="0 0 124 124" style="enable-background:new 0 0 124 124;" xml:space="preserve">-->
<!--                        <g>-->
<!--                            <path d="M112,6H12C5.4,6,0,11.4,0,18s5.4,12,12,12h100c6.6,0,12-5.4,12-12S118.6,6,112,6z"></path>-->
<!--                          <path d="M112,50H12C5.4,50,0,55.4,0,62c0,6.6,5.4,12,12,12h100c6.6,0,12-5.4,12-12C124,55.4,118.6,50,112,50z"></path>-->
<!--                          <path d="M112,94H12c-6.6,0-12,5.4-12,12s5.4,12,12,12h100c6.6,0,12-5.4,12-12S118.6,94,112,94z"></path>-->
<!--                        </g>-->
<!--                    </svg>-->
<!--        <div class="mobile__menu&#45;&#45;dark">-->
<!--          <div class="mobile-menu-header__block">-->
<!--            <div id="menu-main_menu-2" class="menu__list&#45;&#45;mobile2">-->
<!--              <div class="settings header__settings_mobile">-->
<!--                <div class="settings__language settings__language_rectangled">-->
<!--                  <span class="settings__name_mobile">Русский</span>-->
<!--                </div>-->
<!--                <div class="settings__city_mobile settings__city_rectangled">-->
<!--                  <span class="settings__name">Москва</span>-->
<!--                </div>-->
<!--              </div>-->
<!--              <div class="user header__user_mobile">-->
<!--                <div class="user__authentication user__authentication_rectangled">-->
<!--                  <span class="user__authorization_mobile">Войти</span>-->
<!--                </div>-->
<!--                <div class="user__authentication_mobile user__authentication_rectangled">-->
<!--                  <span class="user__registration_mobile">Регистрация</span>-->
<!--                </div>-->
<!--              </div>-->
<!--            </div>-->
<!--            <nav class="mobile_menu&#45;&#45;header">-->
<!--              <ul id="menu-main_menu-1" class="menu__list&#45;&#45;mobile">-->
<!--                <li class="menu-item"><a href="#">Публикации</a></li>-->
<!--                <li class="menu-item"><a href="#">Видео</a></li>-->
<!--                <li class="menu-item"><a href="#">Новости</a></li>-->
<!--                <li class="menu-item"><a href="#">События</a></li>-->
<!--                <li class="menu-item"><a href="#">Организации</a></li>-->
<!--              </ul>-->
<!--            </nav>-->
<!--          </div>-->
<!--        </div>-->
<!--      </div>-->
    </div>
<!--    <div class="wrap wrap_wider header__wrap">-->
<!--      <div class="header__info">-->
<!--        <h1 class="header__title">Найти своего психолога</h1>-->
<!--        <p class="header__text">Несколько тысяч сертифицированных психологов на разных языках. Используйте современную платформу для решения психологических проблем!</p>-->
<!--        <form class="search-form header__search">-->
<!--          <input class="search-form__choose-theme" type="text" placeholder="Выберите тему..." name="theme">-->
<!--          <input class="search-form__button" type="submit" value="Заказать пробную консультацию">-->
<!--        </form>-->
<!--      </div>-->
<!--    </div>-->
    <a href="#content" class="header__arrow header__arrow-see-below">
      <img src="~/assets/arrow-see-bottom.svg" alt="">
    </a>
  </header>
</template>

<style scoped lang="scss">
  @import "~assets/variables";
  .header {
    width: 100%;
    height: 100vh;
    background: url(~assets/header_background.png) no-repeat #263955;
    background-size: cover;
    background-position: top center;
    overflow: hidden;
    &__top {
      width: 96%;
      margin: 0 auto;
      display: grid;
      grid-template-columns: auto auto 1fr 1fr;
      grid-column-gap: 3%;
      -ms-align-items: center;
      align-items: center;
      border-bottom: 0.01em solid darken($white-color, 20);
      height: 70px;
    }
    &__user {
      display: flex;
      flex-wrap: wrap;
      justify-content: flex-end;
      color: #FFFFFF;
    }
    &__arrow > img {
      position: absolute;
      bottom: 5%;
      width: 40px;
      /*max-width: 80px;*/
      /*left: 48.7%;*/
    }
  }
  .logo {
    &__name {
      font-weight: 300;
      font-size: 30px;
      line-height: 100%;
      display: flex;
      align-items: center;
      color: #FFFFFF;
      margin-left: 20px;
    }
    &__link {
      display: flex;
      justify-content: flex-start;
    }
    &__img {
      width: 40px;
      height: 40px;
    }
  }
</style>
