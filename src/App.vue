<script setup>
import{ref} from 'vue'

const name = ref('')
</script>

<template>

<main class="app">
  <section class="greeting">
  <h2 class="title">
  Welcome to your Ingridients list<input type="text" placeholder="Enter Name" v-model="name">
  </h2>
  </section>

  <section class="Ingridients">
  <div class = "Ingridients list">

  <input type="text" placeholder="Your Ingredients!" v-model="Your_list" />
  </div>

  </section>

  <section class ="Add to list">
  </section>

  <section class ="Delete from list">
  </section>
  


</main>



</template>