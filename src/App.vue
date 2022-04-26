<script>
import MenuLateral from "@/components/MenuLateral.vue";
import HeaderNavigation from "./components/HeaderNavigation.vue";
import MainContent from "./components/MainContent.vue";
import FooterContent from "./components/FooterContent.vue";
import BlockContent from "./components/BlockContent.vue";
export default {
  components: {
    MenuLateral,
    HeaderNavigation,
    MainContent,
    FooterContent,
    BlockContent,
  },
};
</script>
<template>
  <MenuLateral />
  <HeaderNavigation />
  <MainContent />
  <FooterContent />
  <main id="content">
    <BlockContent />
    <BlockContent />
    <BlockContent />
    <BlockContent />
    <BlockContent />
    <BlockContent />
  </main>
</template>
<style></style>
