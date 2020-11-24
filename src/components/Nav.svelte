<script>
  function fnMenu() {
    var x = document.getElementById("myLinks");
    if (x.style.display === "block") {
      x.style.display = "none";
    } else {
      x.style.display = "block";
    }
  }
</script>

<style>
</style>

<header>
  <div>
    <img src="/images/LPA_64.png" alt="LPA Logo" />
    <span>Lampasas Pilots Association</span>
  </div>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#meeting">Meetings</a>
    <a href="#contact">Contact</a>
  </nav>

  <img
    id="hamburger"
    src="images/hamburger_32.png"
    alt="Menu"
    on:click={fnMenu} />
</header>
