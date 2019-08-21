<template>
  <div>
    <div class="uk-section uk-section-muted">
      <div class="uk-container uk-text-center">
        <h2 class="uk-text-bold _title">
          Shop curated brands and city essentials, all in on place
        </h2>
      </div>
    </div>
    <!--  -->
    <div class="uk-section uk-inline">
        <div class="uk-child-width-1-5" uk-grid>
          <div class="uk-card uk-card-default uk-card-body">
            <h1 class="_card-title">Maison</h1>
          </div>
          <div class="uk-card uk-card-default uk-card-body">
            <h1 class="_card-title">Construction</h1>
          </div>
          <div class="uk-card uk-card-default uk-card-body">
            <h1 class="_card-title">Cosmetique</h1>
          </div>
          <div class="uk-card uk-card-default uk-card-body">
            <h1 class="_card-title">Electronique</h1>
          </div>
          <div class="uk-card uk-card-default uk-card-body">
            <h1 class="_card-title">Vêtements</h1>
          </div>
        </div>
    </div>
    <!-- <div>
      <h1>
        Laxis Market
      </h1>
      <h2>
        Laxis Market - Le super marché numérique des produits electroniques, medicales, cosmetiques ...
      </h2>
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          class="uk-button"
        >
          Documentation
        </a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          class="uk-button"
        >
          GitHub
        </a>
      </div>
    </div> -->
  </div>
</template>

<script>

export default {
  head: {
    title: 'Laxis Market - Le super marché numérique'
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
