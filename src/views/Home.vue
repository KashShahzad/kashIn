<template>
  <div class="home">
    <introduction />
  </div>
</template>

<script>
// @ is an alias to /src
import introduction from "@/components/Introduction.vue";

export default {
  name: "Home",
  components: {
    introduction
  }
};
</script>
