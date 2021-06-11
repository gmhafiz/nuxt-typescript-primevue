<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">
        npq
      </h1>
      <!--      <font-awesome-icon icon="dollar-sign"  style="font-size: 30px"/>-->
      <div>
        <font-awesome-icon :icon="['fad', 'adjust']" />
        <font-awesome-icon icon="dollar-sign" style="font-size: 30px" />
        <font-awesome-icon icon="cog" />

        <font-awesome-layers class="fa-4x">
          <font-awesome-icon icon="circle" />
          <font-awesome-icon icon="check" transform="shrink-6" :style="{ color: 'white' }" />
        </font-awesome-layers>

        <font-awesome-layers full-width class="fa-4x">
          <font-awesome-icon icon="calendar" />
          <font-awesome-layers-text transform="shrink-8 down-3" value="27" class="fa-inverse" />
        </font-awesome-layers>
      </div>
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          Documentation
        </a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          GitHub
        </a>
      </div>

      <!-- primevue -->
      <div class="">
        <Button label="Submit" icon="pi pi-check" icon-pos="right" />
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
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
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
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
