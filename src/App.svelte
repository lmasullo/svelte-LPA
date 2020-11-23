<script>
  // Import components
  import Nav from "./components/Nav.svelte";
  import Footer from "./components/Footer.svelte";
</script>

<style>
  /* main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  } */

  /* h1 {
    color: #ff3e00;
    text-transform: uppercase;
    font-size: 4em;
    font-weight: 100;
  } */

  /* @media (min-width: 640px) {
    main {
      max-width: none;
    }
  } */
</style>

<main>
  <Nav />
  <div class="carousel">
    <!-- <img src="images/cub_logo_med.png" alt="LPA Logo" /> -->
    <div class="logo">
      <img src="images/LPA_Center_Logo_512.png" alt="LPA Logo" />
    </div>
  </div>

  <div class="card">
    <h3>Card Heading</h3>
    <p>
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
      tempor
    </p>
    <button>Accept</button>
  </div>

  <div class="card">
    <h3>Card Heading</h3>
    <p>
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
      tempor
    </p>
    <button>Accept</button>
  </div>

  <Footer />

</main>
