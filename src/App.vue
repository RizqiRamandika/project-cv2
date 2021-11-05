<template>
  <div id="app">
    <div class="row py-4">
      <CvSatu />
      <div>
        <CvDua />
      </div>
    </div>
  </div>
</template>

<script>
import CvSatu from "./components/CvSatu.vue";
import CvDua from "./components/CvDua.vue";

export default {
  name: "app",
  components: {
    CvSatu,
    CvDua,
  },
};
</script>