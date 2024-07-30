<script setup>
import HelloWorld from '@/components/helloWorld.vue';

import { reactive } from 'vue'

const hello = HelloWorld;
const welcome = reactive('welcome to the home page on this website')

</script>

<template>
  <main>
    {{ welcome }}
    <hello class="hello" />
  </main>
</template>

<style>
.hello {
  background-color: aqua;
  color: black;
  padding: 10px;
  font-size: 30px;
}
</style>
