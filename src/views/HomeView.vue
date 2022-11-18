<template>
<Banner />
  <div class="main-container">
   <h1>Monte o seu burguer: </h1>
   <burgerform />
  </div>
</template>

<script>
import Banner from "../components/Banner.vue"
import burgerform from "../components/burgerform.vue"

export default {
  name: "Home",
  components: {
    Banner,
    burgerform,
  }
}
</script>
