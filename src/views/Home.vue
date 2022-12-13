<template>
  <div class="home">
    <span class="text-3xl font-bold underline text-pink-500 flex"
      >Hello world!</span
    >
    <font-awesome-sample />
  </div>
</template>

<script lang="ts">
import FontAwesomeSample from "@/components/FontAwesomeSample.vue";
import { Options, Vue } from "vue-class-component";

@Options({
  components: { FontAwesomeSample },
})
export default class Home extends Vue {}
</script>
