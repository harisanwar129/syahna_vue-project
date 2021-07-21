<template>
  <div class="home">
    <HeaderShayna />
    <HeroShayna />
    <WomenShayna />
    <InstaShayna />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
// import HeaderShayna from "@/components/HeaderShayna.vue";
import HeaderShayna from "../components/HeaderShayna.vue";
import HeroShayna from "../components/HeroShayna.vue";
import WomenShayna from "../components/WomenShayna.vue";
import InstaShayna from "../components/InstaShayna.vue";
export default {
  name: "Home",
  components: {
    HeaderShayna,
    HeroShayna,
    WomenShayna,
    InstaShayna,
  },
};
</script>
