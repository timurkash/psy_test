<script>
  import Prev from '~/components/Prev.vue'
  import LandingHeader from '~/components/landing/Header.vue'

  export default {
    components: {
      Prev,
      LandingHeader,
    }
  }
</script>

<template>
  <div class="container">
    <landing-header />
    <prev />
<!--    <div>-->
<!--      <logo />-->
<!--      <h1 class="title">-->
<!--        psy-test-->
<!--      </h1>-->
<!--      <h2 class="subtitle">-->
<!--        test-->
<!--      </h2>-->
<!--      <div class="links">-->
<!--        <a-->
<!--          href="https://nuxtjs.org/"-->
<!--          target="_blank"-->
<!--          class="button button&#45;&#45;green"-->
<!--        >-->
<!--          Documentation-->
<!--        </a>-->
<!--        <a-->
<!--          href="https://github.com/nuxt/nuxt.js"-->
<!--          target="_blank"-->
<!--          class="button button&#45;&#45;grey"-->
<!--        >-->
<!--          GitHub-->
<!--        </a>-->
<!--      </div>-->
<!--    </div>-->
  </div>
</template>

<style lang="scss" scoped>
  .container {
    margin: 0 auto;
    min-height: 100vh;
    /*display: block;*/
    justify-content: center;
    align-items: center;
    text-align: center;
  }

  /*.title {*/
  /*  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,*/
  /*  'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;*/
  /*  display: block;*/
  /*  font-weight: 300;*/
  /*  font-size: 100px;*/
  /*  color: #35495e;*/
  /*  letter-spacing: 1px;*/
  /*}*/

  /*.subtitle {*/
  /*  font-weight: 300;*/
  /*  font-size: 42px;*/
  /*  color: #526488;*/
  /*  word-spacing: 5px;*/
  /*  padding-bottom: 15px;*/
  /*}*/

  /*.links {*/
  /*  padding-top: 15px;*/
  /*}*/

  /*.button {*/
  /*  margin: 10px;*/
  /*  &--green {*/
  /*    display: inline-block;*/
  /*    border-radius: 4px;*/
  /*    border: 1px solid #3b8070;*/
  /*    color: #3b8070;*/
  /*    text-decoration: none;*/
  /*    padding: 10px 30px;*/
  /*    &:hover {*/
  /*      color: #fff;*/
  /*      background-color: #3b8070;*/
  /*    }*/
  /*  }*/
  /*  &--grey {*/
  /*    display: inline-block;*/
  /*    border-radius: 4px;*/
  /*    border: 1px solid #35495e;*/
  /*    color: #35495e;*/
  /*    text-decoration: none;*/
  /*    padding: 10px 30px;*/
  /*    &:hover {*/
  /*      color: #fff;*/
  /*      background-color: #35495e;*/
  /*    }*/
  /*  }*/
  /*}*/
</style>
