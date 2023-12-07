<script>
	import Cards from './Cards.svelte';
  import Card from './Cards.svelte'; 
</script>
<div class="main-content">
  <!-- Your main page content goes here -->

  <!-- Include the Card component -->
  <Cards />
</div>

<style>
  /* Add any page-specific styling here */
  .main-content {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }
</style>