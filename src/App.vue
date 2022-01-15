<template>
   <h1 class="text-center">{{ tittle }}</h1>
   <Calculator />
</template>

<script>
import Calculator from "./components/Calculator.vue";

export default {
   name: "App",
   components: {
      Calculator,
   },
   data() {
      return {
         tittle: "Hello, Use Calculator online",
      };
   },
};
</script>

<style>
body {
   background-color: #bff7e4;
}
</style>
