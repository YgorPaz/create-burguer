<template>
  <div id="main-banner">
    <h1>Faça seu Burger</h1>
  </div>
</template>

<script>
export default {
  name: "Banner",
  data() {
    return {};
  },
};
</script>

<style scoped>
#main-banner {
  background-image: url("../../public/img/burger.jpg");
  background-position: 0 -250px;
  background-size: cover;
  height: 500px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
  background-repeat: no-repeat;
}

#main-banner h1 {
  color: #fff;
  text-align: center;
  font-size: 50px;
  background-color: #222;
  padding: 20px 40px;
  margin-left: 150px;
  margin-top: 20px;
}
/*CSS Mobile */
@media (max-width: 600px) {
  #main-banner {
    background-image: url("../../public/img/burger.jpg");
    background-size: contain;
    background-position: 0 0;
    height: 350px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
    background-repeat: no-repeat;
  }
  #main-banner h1 {
    color: #fff;
    text-align: center;
    font-size: 18px;
    background-color: #222;
    padding: 10px 20px;
  }
}
</style>
