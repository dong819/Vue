<template>
  <div>
    <Header />
    <Footer />
  </div>
</template>

<script>
//引入组件
import Header from "./components/Header";
import Footer from "./components/Footer";

export default {
  name: "App",
  components: {
    //注册组件
    Header,
    Footer
  }
};
</script>

<style>
</style>