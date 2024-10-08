<style lang="css" src="./assets/css/custom.css"></style>
<template>
  <div id="readability-matters-site">
    <header>
      <a id="logo-link" href="https://readabilitymatters.org/">
        <img src="./assets/images/rm-2024.png">
      </a>
    </header>
    <Sandbox />
  </div>
</template>
<script>
  import Sandbox from "./components/Sandbox.vue";
  
  export default {
    name: "TuneYourText",
    components: {
      Sandbox,
    },
    created() {
      this.$store.dispatch("injectStyles");
    },
    data: () => ({
    }),
    computed: {
    },
    methods: {
    },
    mounted: function() {
    }
  };
</script>