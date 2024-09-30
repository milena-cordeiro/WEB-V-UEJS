<template>
  <div id="app">
    <h1>Calculator</h1>
    <Calculator />
  </div>
</template>

<script>
import Calculator from './main/Calculator.vue'
export default {
    components: {
        Calculator
    }
}
</script>

<style>
/* @font-face {
    font-family: "RobotoMono";
    src: url("./fonts/RobotoMono-Regular.ttf");
} */

* {
    font-family: "RobotoMono", monospace;
}

body {
    margin: 0;
}

#app {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    justify-content: center;
    height: 100vh;
    color: #f0f0f0;
    background: linear-gradient(to right, rgb(83,105,118), rgb(41,46,73));
}


</style>