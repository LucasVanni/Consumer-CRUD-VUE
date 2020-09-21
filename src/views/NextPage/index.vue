<template>
  <div class="next">
    <Container>
      <h1>Hello People</h1>
    </Container>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import { Container } from "@/views/NextPage/styles.ts";

@Options({
  components: {
    Container
  }
})
export default class NewPage extends Vue {}
</script>
