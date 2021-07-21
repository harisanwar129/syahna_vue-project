<template>
  <div class="product">
    <HeaderShayna />
    <p>Product Saya Akan Berada Di Sini</p>
    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
// import HeaderShayna from "@/components/HeaderShayna.vue";
import HeaderShayna from "../components/HeaderShayna.vue";

import FooterShayna from "../components/FooterShayna.vue";
export default {
  name: "Product",
  components: {
    HeaderShayna,

    FooterShayna,
  },
};
</script>
