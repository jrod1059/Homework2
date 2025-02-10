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
  <div class = "options">
    <label>
      <input type = "radio" name="category" value = "Add to list" v-model="Add_list">
      <span class = "bubble list"></span>
      <div>Add to List</div>
    </label>
    </div>
  </section>

  <section class ="Delete from list">
  <div class = "options">
    <label>
      <input type = "radio" name="category" value = "Delete from list" v-model="Delete_list">
      <span class = "bubble list"></span>
      <div>Delete from List</div>
    </label>
    </div>
  </section>
  


</main>



</template>