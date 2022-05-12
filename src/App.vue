<script setup>
import {ref, computed} from 'vue'

const questions = ref([
  {
    question: "When was the first man on the moon ?",
    answer: 0,
    options: [
      "1969",
      "1968",
      "1967"
    ],
    selected: null
  },
  {
  question: "What is two zero two one ?",
  answer: 2,
  options: [
    "2011",
    "0021",
    "2121",
    "0011"
  ],
  selected: null
  },
])
</script>

<template>
<h1>Hello World</h1>
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Montserrat', sans-serif;
}
body {
  background-color: #271C36;
  color: #FFF;
}
</style>
