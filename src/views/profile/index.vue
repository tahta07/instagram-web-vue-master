<template>
  <div class="home">
    <CostumText tag="h1">Profile</CostumText>
    <router-view />
  </div>
</template>

<script>
import CostumText from "@/components/CostumText.vue";

export default {
  name: "Profile",
  components: {
    CostumText
  }
};
</script>

<style scoped></style>
