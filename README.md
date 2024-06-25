<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Little Lemon</title>
  <link rel="stylesheet" href="css/little-lemon.css">
</head>
<body>
  <header>
    <div class="header-container">
      <img src="images/header-logo.png" alt="Header Logo" id="header-logo">
      <nav>
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#menu">Menu</a></li>
          <li><a href="#book">Book</a></li>
          <li><a href="#about">About</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section id="promo-banner">
    <img src="images/promo-banner.jpg" alt="Promotional Banner">
    <div class="promo-description">
      <h2>30% Off This Weekend</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris.</p>
    </div>
  </section>

  <section id="features">
    <div class="feature">
      <img src="images/menu.jpg" alt="Our New Menu" class="feature-image">
      <div class="feature-description">
        <h3>Our New Menu</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris.</p>
        <a href="#">See our new menu</a>
      </div>
    </div>
    <div class="feature">
      <img src="images/book.jpg" alt="Book a Table" class="feature-image">
      <div class="feature-description">
        <h3>Book a Table</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris.</p>
        <a href="#">Book your table now</a>
      </div>
    </div>
    <div class="feature">
      <img src="images/opening-hours.jpg" alt="Opening Hours" class="feature-image">
      <div class="feature-description">
        <h3>Opening Hours</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris.</p>
        <p>Mon - Fri: 2pm - 10pm<br>Sat: 2pm - 11pm<br>Sun: 2pm - 9pm</p>
      </div>
    </div>
  </section>

  <footer>
    <img src="images/footer-logo.png" alt="Footer Logo" id="footer-logo">
    <p>&copy; 2024 Little Lemon. All rights reserved.</p>
  </footer>

  <button onclick="scrollToTop()" id="scrollToTopBtn" title="Go to top">Top</button>

  <script>
    function scrollToTop() {
      document.documentElement.scrollTop = 0;
    }
  </script>
</body>
</html>
