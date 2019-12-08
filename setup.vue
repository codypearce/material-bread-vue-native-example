<template>
  <app></app>
</template>

<script>
import Vue from "vue-native-core";
import { VueMaterialBread } from "material-bread";

import App from "./src/App.vue";
// registering all components to the global scope of the Vue
Vue.use(VueMaterialBread);

export default {
  components: { App }
};
</script>
