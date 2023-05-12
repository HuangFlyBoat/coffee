<template>
  <div>
    <Header>
      <HeaderNav></HeaderNav>
    </Header>
    <div><RouterView></RouterView></div>
    <Footer>
      <FooterBar></FooterBar>
    </Footer>
  </div>
</template>

<script>
import { defineComponent } from 'vue';
import HeaderNav from '@/components/HeaderNav.vue';
import FooterBar from '@/components/FooterBar.vue';

export default defineComponent({
  components: { FooterBar, HeaderNav }
});
</script>

<style scoped></style>
