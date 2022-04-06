<template>
  <v-app>
    <v-main class="d-flex flex-column align-center justify-center">
      <h1>Bem-vindo</h1>
      <NuxtLink :to="{name: 'index'}">Home</NuxtLink>
      <NuxtLink :to="{name: 'produtos'}">Produtos</NuxtLink>

      <Nuxt />
    </v-main>
  </v-app>
</template>

<script>
export default {
  data () {
    return {
    }
  }
}
</script>