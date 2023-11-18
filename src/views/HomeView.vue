<template>
  <Banner />
  <div class="main-container">
    <h1>Monte seu Burguer:</h1>
    <BurgerFormVue />
  </div>
</template>

<script>
import BurgerFormVue from "@/components/BurgerForm.vue";
import Banner from "../components/Banner.vue";
export default {
  name: "HomeView",
  components: {
    Banner,
    BurgerFormVue,
  },
};
</script>
