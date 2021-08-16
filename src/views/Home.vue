<template>
  <div class="home">
    <CopyTool />
  </div>
</template>

<script>
// @ is an alias to /src
import CopyTool from "@/components/CopyTool.vue";

export default {
  name: "Home",
  components: {
    CopyTool,
  },
};
</script>
