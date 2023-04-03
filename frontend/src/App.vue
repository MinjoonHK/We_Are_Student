<template>
  <Header/>
  <RouterView/>
</template>

<script>
import Header from "@/components/Header.vue"
import {useRoute} from "vue-router";

export default {
  name: 'App',
  components: {
    Header
  },
setup() {
  const route = useRoute();
}
}
</script>

<style>

</style>
