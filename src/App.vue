<template>
  <v-app>
    

    <v-main>
      <ByLawComponent />
    </v-main>
  </v-app>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

import ByLawComponent from "@/components/ByLawComponent.vue";

@Component({
  components: {
    ByLawComponent,
  },
})
export default class App extends Vue {}
</script>
