<script>
  import Footer from "./Footer.svelte";
  import Left from "./Left.svelte";
  import MainDown from "./MainDown.svelte";
  import MainUp from "./MainUp.svelte";
</script>

<!-- Page Container -->
<div class="w3-content w3-margin-top" style="max-width:1400px;">
  <!-- The Grid -->
  <div class="w3-row-padding">
    <Left />
    <!-- Right Column -->
    <div class="w3-twothird">
      <MainUp />
      <MainDown />
      <!-- End Right Column -->
    </div>

    <!-- End Grid -->
  </div>
  <!-- End Page Container -->
</div>
<Footer />
