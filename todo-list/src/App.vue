<template>
  <div :class="$style.container">
    <AppHeader />
    <AppContent />
    <AppFooter />
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import AppHeader from "./components/AppHeader/index.vue";
import AppContent from "./components/AppContent/index.vue";
import AppFooter from "./components/AppFooter/index.vue";

@Options({
  components: {
    AppHeader,
    AppContent,
    AppFooter,
  },
})
export default class App extends Vue {}
</script>

<style module lang="scss">
.container {
  font-size: 18px;
}
</style>
