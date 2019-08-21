<template>
  <div>
    <Header />
    <nuxt />
  </div>
</template>

<script>
import Header from '@/components/Header'

export default {
  components: {
    Header
  }
}
</script>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  letter-spacing: -0.5px;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
._title {
  font-size: 36px;
    letter-spacing: -2px;
    line-height: 40px;
}
._card-title {
    font-size: 24px;
    font-weight: 700;
    letter-spacing: -0.6px;
    line-height: 28px;
}
/* UIKit */
.uk-navbar-container:not(.uk-navbar-transparent) {
    background: #fff!important;
}
</style>
