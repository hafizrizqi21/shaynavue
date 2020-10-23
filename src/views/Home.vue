<template>
  <div class="home">
    <HeaderShayna />
    <HeroCarousel />
    <ProductCarousel />
    <InstaShayna />
    <PartnerLogo />
    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderShayna from "@/components/HeaderShayna";
import HeroCarousel from "@/components/HeroCarousel";
import ProductCarousel from "@/components/ProductCarousel";
import InstaShayna from "@/components/InstaShayna";
import PartnerLogo from "@/components/PartnerLogo";
import FooterShayna from "@/components/FooterShayna";

export default {
  name: "Home",
  components: {
    HeaderShayna,
    HeroCarousel,
    ProductCarousel,
    InstaShayna,
    PartnerLogo,
    FooterShayna,
  },
};
</script>
