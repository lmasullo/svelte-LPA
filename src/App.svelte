<script>
  // Import components
  import Nav from "./components/Nav.svelte";
  import Footer from "./components/Footer.svelte";
</script>

<main>
  <!-- Nav bar component -->
  <Nav />

  <!-- Hamburger menu items -->
  <div id="myLinks">
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#meeting">Meetings</a>
    <a href="#contact">Contact</a>
  </div>

  <!-- Main logo with image at top of page -->
  <div id="home" class="carousel ">
    <div class="logo">
      <img class="responsiveImage" src="images/LPA_Center_Logo.png" alt="LPA Logo" />
    </div>
  </div>

  <!-- About Card -->
  <div id="about" class="card">
    <h3>About the LPA</h3>
    <p>Lampasas Pilots Association was established in the early 1970s by Jane S. King. Jane arrived in Lampasas as a CFI and provided training for many of Lampasas' pilots. She organized those early pilots that were hanging around the airport into what is now the Lampasas Pilots Association.</p>
    <p>Thank you Jane!</p>
  </div>

  <!-- Meeting Card -->
  <div id="meeting" class="card">
    <h3>LPA Meeting</h3>
    <p>
      Our next meeting will be Saturday, September 10, 2022, 0800.
      <br />
      The meeting will be held in a private room at Putter's and Gutters on 281 South in Lampasas, TX.
    </p>
    <p>
      <a target="_blank" href="https://www.puttersandgutters.com/"> Click Here for Their Website </a>
    </p>
  </div>

  <!-- Contact Card -->
  <div id="contact" class="card">
    <h3>Contact Us</h3>
    <p>
      Interested in joining the Lampasas Pilots Association or just want some more information? Send us a message.
      <br />
      <a target="_blank" href="mailto:info@lampasaspilotsassociation.org"> Click to Email - info@lampasaspilotsassociation.org </a>
    </p>
    <!-- Google Map to KLZZ -->
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d7688.606183263735!2d-98.19847999865405!3d31.09607643966836!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xe7cc403c4b711cbd!2sLampasas%20Airport-LZZ!5e0!3m2!1sen!2sus!4v1606148239591!5m2!1sen!2sus" width="95%" height="450" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0" title="Embedded Google Map of KLZZ" />
    <p>
      <a target="_blank" href="http://www.airnav.com/airport/KLZZ"> KLZZ at AirNav.com </a>
    </p>
  </div>

  <!-- Footer component -->
  <Footer />
</main>

<main />
