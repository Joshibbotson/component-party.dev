<script setup>
import { ref } from "vue";

const picked = ref("red");
</script>

<template>
  <div>Picked: {{ picked }}</div>

  <input id="blue-pill" v-model="picked" type="radio" value="blue" />
  <label for="blue-pill">Blue pill</label>

  <input id="red-pill" v-model="picked" type="radio" value="red" />
  <label for="red-pill">Red pill</label>
</template>
