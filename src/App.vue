<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>
  </header>

  <main>
      <body style="margin: 0; height: 100vh; background-color: rgb(31, 31, 31);">
    <div style="display: flex; justify-content: center; align-items: center; width: 100%; height: 100%; color: white; flex-direction: column;">
      <H1 style="font-size: 40px; font-weight: 900; font-style: italic;" >Il sito è momentaneamente in manutenzione.</H1>
      <h2>Ci scusiamo per eventuali disagi.</h2>
    </div>
  </body>
    <!-- <TheWelcome /> -->
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
