<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1 class="Black">{{ msg }}</h1>
    <h3>
      About Me <br>
      <a href="https://www.instagram.com/mhfa4898/" target="_blank" rel="noopener"> <img src="@/assets/ig.png" alt=""> </a> &
      <a href="https://github.com/MhFahmi48/TugasFahmi" target="_blank" rel="noopener"><img src="@/assets/github.png" alt=""></a>.
    </h3>
  </div>
</template>

<style scoped>
img {
  width: 5%;
  
}


h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
