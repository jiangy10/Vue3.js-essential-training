<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
// import Checklist from './components/Checklist.vue'
</script>

<template>
  <!-- <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>
  </header> -->

  <main>
    <!-- <TheWelcome /> -->
    <h1>Multiple Checkboxes</h1>
    <div>
      <input v-model = "checkBoxes" value = "first" class = "form-check-input" type = "checkbox" id = "cb1">
      <label for = "cb1">First</label>
    </div>
    <div>
      <input v-model = "checkBoxes" value = "second" class = "form-check-input" type = "checkbox" id = "cb2">
      <label for = "cb2">Second</label>
    </div>
    <div>
      <input v-model = "checkBoxes" value = "third" class = "form-check-input" type = "checkbox" id = "cb3">
      <label for = "cb3">Third</label>
    </div>
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
