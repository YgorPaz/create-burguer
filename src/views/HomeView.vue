<template>
  <Banner />
  <div class="main-container-home">
    <h1>Monte seu Burger</h1>
  </div>
  <BurgerForm />
</template>

<script>
import Banner from "../components/Banner.vue";
import BurgerForm from "../components/BurgerForm.vue";
export default {
  name: "Home",
  components: {
    Banner,
    BurgerForm,
  },
};
</script>
