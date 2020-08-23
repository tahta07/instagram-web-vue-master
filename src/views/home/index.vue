<template>
  <div class="home">
    <h1>Home</h1>
    <CostumText class="a1" tag="p">Merhaba Dünya</CostumText>
    <CostumText class="a2" tag="p" size="small">Merhaba Dünya</CostumText>
    <CostumText class="a3" tag="p" size="xsmall">Merhaba Dünya</CostumText>
    <CostumText class="a4" tag="p" size="xxsmall">Merhaba Dünya</CostumText>
    <IconHome/>
  </div>
</template>

<script>
import CostumText from "@/components/CostumText.vue";
import IconHome from "@/icons/home.svg"
export default {
  name: "Home",
  components:{
    CostumText,
    IconHome
  }
};
</script>

<style scoped>
.a1{
  color: rgb(var(--e62))
}
.a2{
  color: rgb(var(--cdd))
}
.a3{
  color: rgb(var(--b2f))
}
.a4{
  color: rgb(var(--a22))
}
</style>
