<script lang="ts">
  import "./dist/style.css";
  import Hero from "./lib/Hero.svelte";
  import Second from "./lib/Second.svelte";
  import Third from "./lib/Third.svelte";
  import Fourth from "./lib/Fourth.svelte";
  import Footer from "./lib/Footer.svelte";
</script>

<main class="wrapper">
  <Hero class="section section__1" />
  <Second class="section section__2" />
  <Third class="section section__3" />
  <Fourth class="section section__4" />

  <Footer class="section section__3" />
</main>

<style lang="scss">
  //   section {
  //   height: 100vh;
  //   display: flex;
  //   flex-flow: column;
  //   justify-content: center;
  //   align-items: center;
  //   gap: 1rem;
  // }
</style>
