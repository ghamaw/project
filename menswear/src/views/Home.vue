<template>
  <div class="home">
    <Header/>
    <HeroWeb/>
    <Catalog/>
    <InstaProduct/>
    <Footer/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import Header from "@/components/Header.vue";
import HeroWeb from "@/components/HeroWeb.vue";
import Catalog from "@/components/Catalog.vue";
import InstaProduct from "@/components/InstaProduct.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "home",
  components: {
    Header,
    HeroWeb,
    Catalog,
    InstaProduct,
    Footer
  },
};
</script>
