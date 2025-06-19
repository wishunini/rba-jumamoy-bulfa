<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>TTS</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header class="header">
      <nav class="nav-container">
                      <a href="#backtomainpage" class="nav-link">Back to main page</a>
          <a href="#home" class="logo">
              <img src="logo.png" alt="Logo" class="logo-img">
              <span class="logo-text">Tukuran Tourist Spots</span>
            </a>
          <ul class="nav-menu">
            <li class="nav-item">
                <a href="#home" class="nav-link">Home</a>
            </li>
            <li class="nav-item">
                <a href="#destination" class="nav-link">Facilities</a>
            </li>
                <li class="nav-item">
                    <a href="#gallery" class="nav-link">Gallery</a>
                </li>
                <li class="nav-item">
                    <a href="#developers" class="nav-link">Developers</a>
                </li>
            </ul>
        </nav>
    </header>


    <main class="main-content">
        
        <section id="home" class="hero">
            <div class="hero-slideshow">
                
                <div class="hero-slide active" style="background-image: url('RBA cottages.jpg')"></div> 
            </div>
            <div class="hero-content">
                <h1>RBA Beach</h1>
                <div class="typing-text">
                    <span id="typing-output" class="typing-animation"></span>
                </div>
            </div>
        </section>
        <section id="destination" class="featured-destinations">
            <h2 class="section-title"><span>FACILITIES</span></h2>
            
            <div class="destination-item">
                <div class="destination-image">
                    <div class="slideshow-container" data-slideshow="1">
                        <div class="slide active" style="background-image: url('rba cottages2.jpg')"></div>
                    </div>
                </div>
                <div class="destination-content">
                    <h3>Cottages </h3>
                    <p>The cottages where you can put all your things, rest, and party.</p>
                    <li>₱300.00 Cottage</li>
                </div>
            </div>
        
                        <div class="destination-item">
                <div class="destination-image">
                    <div class="slideshow-container" data-slideshow="1">
                        <div class="slide active" style="background-image: url('rba karaoke area.jpg')"></div> 
                    </div>
                </div>
                <div class="destination-content">
                    <h3>karaoke Area</h3>
                    <p>Show your talent here as a fantastic singer for 5 pesos you can enjoy two songs. </p>
                </div>
            </div>
                        <div class="destination-item">
                <div class="destination-image">
                    <div class="slideshow-container" data-slideshow="1">
                        <div class="slide active" style="background-image: url('rba cr.jpg')"></div>
                    </div>
                </div>
                <div class="destination-content">
                    <h3>Comfort Room</h3>
                    <p>Find your comfort here.</p>
                </div>
            </div>
                        <div class="destination-item">
                <div class="destination-image">
                    <div class="slideshow-container" data-slideshow="1">
                        <div class="slide active" style="background-image: url('rba store.jpg')"></div>
                    </div>
                </div>
                <div class="destination-content">
                    <h3>Store</h3>
                    <p>Forgot to purchase your foods? No problem.</p>
                </div>
            </div>

            
        <section id="gallery" class="featured-destinations">
            <h2 class="section-title"><span>Gallery</span></h2>

        <div class="gallery">
            <img src="RBA bridge below.jpg" alt="Image 1"> 
            <img src="RBA bridge.jpg" alt="Image 2"> 
            <img src="RBA cottages.jpg" alt="Image 3"> 
            <img src="rba cottages2.jpg" alt="Image 4">
            <img src="rba entrance.jpg" alt="Image 5">
            <img src="rba karaoke area.jpg" alt="Image 6">
            <img src="rba cr.jpg" alt="Image 7">
            <img src="rba store.jpg" alt="Image 8">
        </div>
    </section>

        <div class="modal" id="modal">
    <span class="close" id="closeBtn">&times;</span>
    <button class="modal-nav" id="prevBtn">&#10094;</button>
    <img id="modalImg" src="" alt="Full View">
    <button class="modal-nav" id="nextBtn">&#10095;</button>
        </div>
 

        <section id="developers" class="developers">
            <h2 class="section-title"><span>Developers</span></h2>
            <div class="developers-grid">
                <div class="developer-card">
                    <div class="developer-video">
                        <img src="jerryb.jpeg" alt="Img" class="developer-video">
                    </div>
                    <div class="developer-name">Jerry A. Bulfa</div>
                    <div style="color: transparent;" class="developer-role"></div>
                    <div class="developer-bio">Photographer/videographer</div>
                </div>
                <div class="developer-card">
                    <div class="developer-video">
                        <img src="CrsmieJ.jpeg" alt="Img" class="developer-video">
                    </div>
                    <div class="developer-name">Crismie V. Jumamoy</div> 
                    <div style="color: transparent;" class="developer-role"></div>
                    <div class="developer-bio">Web developer</div> 
            </div>
        </section>
  
    <footer class="footer">
        <div class="footer-content">
            <div class="footer-section">
                <h4>Tukuran Tourist Spots</h4>
                <ul class="footer-links">
                    <li><a href="#home">Home</a></li>
                    <li><a href="#destination">Facilities</a></li>
                    <li><a href="#gallery">Gallery</a></li>
                    <li><a href="#developers">Developers</a></li>
                </ul>
            </div>
  <div class="footer-section">
    <h4>Follow Us</h4>
        <div class="social-buttons">
            <a href="https://www.facebook.com/share/16cK27pfbX/" class="social-btn facebook">Facebook</a>
            <a href="#" class="social-btn twitter">Twitter</a> 
            <a href="https://www.instagram.com/itscrsmiemadear?igsh=emkyajZua3A2NnZ4" class="social-btn instagram">Instagram</a>
        </div>
  </div>
    </div>
        <div class="footer-bottom">
            <p>&copy; 2025 Tukuran Tourist Spots. All rights reserved. Discover your outing.</p>
        </div>
    </footer>
  <script src="script.js"></script>
</body>
</html>
