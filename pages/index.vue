<template>
  <div class="container">
    <Hooper>
      <Slide class="slide is-1">1</Slide>
      <Slide class="slide is-2">2</Slide>
      <Slide class="slide is-3">3</Slide>
      <Slide class="slide is-4">4</Slide>
      <Slide class="slide is-5">5</Slide>
    </Hooper>
  </div>
</template>

<script>
import { Slide, Hooper } from 'hooper'

export default {
  components: {
    Slide,
    Hooper
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.hooper {
  height: 100vh;
}

.slide {
  font-size: 100px;
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
}

.is-1 {
  background: red;
}

.is-2 {
  background: purple;
}

.is-3 {
  background: blue;
}

.is-4 {
  background: green;
}

.is-5 {
  background: gray;
}
</style>
