<script>

export default {
  name: `App`,


data() {
  return {
    message: "Anthony",
    image: "https://www.greenme.it/wp-content/uploads/2020/08/curioso-come-george.jpg",
  }
 },
 methods: {

 }
}
</script>

<template>

  <h1>Ciao {{ message }}</h1>
  <img :src="image">

</template>

<style>
</style>