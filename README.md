<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
  <title>Calumbuyan Point</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <style>
  .hero {
    background: url('images/hero2.png') no-repeat center center;
    background-size: cover;
    color: rgb(255, 255, 255);
    height: 500px;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
  }
  .hero h1 {
    font-size: 5rem;
  }
  .hero p {
    font-size: 2rem;
  }
  .rooms, .amenities {
    padding: 60px 0;
  }
  .contact-form {
    background: #f9f9f9;
    padding: 60px 0;
  }
  .navbar-brand img {
    height: 100px; /* Adjust as needed */
    margin-right: 10px;
  }
  .image-container {
    position: relative;
    width: 100%;
    height: 375px; /* Fixed height for uniform size */
    overflow: hidden;
  }
  .image-container img {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover; /* Ensures images cover the container while maintaining aspect ratio */
    opacity: 0;
    transition: opacity 1s;
  }
  .image-container img.active {
    opacity: 1;
  }
  </style>
</head>
<body>

  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" href="#">
      <img src="images/CP-1.png" alt="Resort Logo">
      Calumbuyan Point
    </a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item active">
          <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#about">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#rooms">Rooms</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#amenities">Amenities</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#contact">Contact</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Hero Section -->
  <div class="hero">
    <div class="hero-content">
      <h1>Welcome to Calumbuyan Point</h1>
      <p>Experience the hidden paradise.</p>
      <a class="btn btn-primary btn-lg" href="#rooms" role="button">View Rooms</a>
    </div>
  </div>

  <!-- About Section -->
  <div id="about" class="about container text-center">
    <h2>About Us</h2>
    <p>Welcome to Calumbuyan Point, your perfect getaway destination where luxury meets nature. Our resort offers a serene escape with breathtaking views, exceptional service, and a variety of amenities designed to make your stay unforgettable. Whether you're here for a romantic retreat, a family vacation, or a solo adventure, Calumbuyan Point provides an unparalleled experience that will leave you refreshed and rejuvenated.</p>
  </div>
  <div id="about" class="about container text-center">
    <h2>Our Story</h2>
    <p>Calumbuyan Point was established by the Palacio family in 2021, with a dream to create a tranquil escape where visitors could experience the beauty of the Calatagan beaches in a warm and welcoming atmosphere. Over the years, our resort has grown, but our commitment to family values and personal service remains at the heart of everything we do.</p>
  </div>
  <div id="about" class="about container text-center">
    <h2>Our Commitment</h2>
    <p>As a family-owned resort, we pride ourselves on offering personalized service and attention to detail. Our mission is to create a home away from home for every guest, ensuring your stay is as relaxing and enjoyable as possible. From our meticulously maintained grounds to our friendly and attentive staff, we strive to provide an exceptional experience that will leave you with cherished memories.</p>
  </div>

  <!-- Rooms Section -->
  <div id="rooms" class="rooms container text-center">
    <h2>Our Rooms</h2>
    <div class="row">
      <div class="col-md-4">
        <div class="image-container">
          <img src="images/TeepeeHut.png" class="img-fluid active" alt="Teepee Hut">
          <img src="images/Teepee2.png" class="img-fluid" alt="Teepee Hut 2">
          <img src="images/Teepee3.png" class="img-fluid" alt="Teepee Hut 3">
        </div>
        <h3>Teepee Hut</h3>
        <p>Perfect for a Couple or a new family!</p>
      </div>
      <div class="col-md-4">
        <div class="image-container">
          <img src="images/OhanaHut.png" class="img-fluid active" alt="Ohana Hut">
          <img src="images/OhanaHut2.png" class="img-fluid" alt="Ohana Hut 2">
          <img src="images/OhanaHut3.png" class="img-fluid" alt="Ohana Hut 3">
        </div>
        <h3>Ohana</h3>
        <p>Ohana means family, and family always sticks together! This hut is perfect for a family of 5!</p>
      </div>
      <div class="col-md-4">
        <div class="image-container">
          <img src="images/MayaVilla.png" class="img-fluid active" alt="Maya Villa">
          <img src="images/MayaVilla2.png" class="img-fluid" alt="Maya Villa 2">
          <img src="images/MayaVilla3.png" class="img-fluid" alt="Maya Villa 3">
        </div>
        <h3>Maya Villa</h3>
        <p>Private villas with a beautiful view.</p>
      </div>
    </div>
  </div>

  <!-- Amenities Section -->
  <div id="amenities" class="amenities container text-center">
    <h2>Amenities</h2>
    <div class="row">
      <div class="col-md-4">
        <div class="image-container">
          <img src="images/CaféDesto.png" class="img-fluid active" alt="Café Desto">
          <img src="images/CaféDesto2.png" class="img-fluid" alt="Café Desto 2">
          <img src="images/CaféDesto3.png" class="img-fluid" alt="Café Desto 3">
        </div>
        <h3>Café Desto</h3>
        <p>Enjoy a cup of coffee with your loveones or friends, with an amazing view of the sea!</p>
      </div>
      <div class="col-md-4">
        <div class="image-container">
          <img src="images/Pool1.jpg" class="img-fluid active" alt="Swimming Pool">
          <img src="images/Pool.jpg" class="img-fluid" alt="Swimming Pool 2">
          <img src="images/Pool3.jpg" class="img-fluid" alt="Swimming Pool 3">
        </div>
        <h3>Swimming Pool</h3>
        <p>Take a dip in our infinity pool.</p>
      </div>
      <div class="col-md-4">
        <div class="image-container">
          <img src="images/Poolside Cottage.png" class="img-fluid active" alt="Poolside Cottage">
          <img src="images/PoolsideCottage2.png" class="img-fluid" alt="Poolside Cottage 2">
          <img src="images/PoolsideCottage3.png" class="img-fluid" alt="Poolside Cottage 3">
        </div>
        <h3>Poolside Cottage</h3>
        <p>Relax beside the pool with our Poolside Cottages!</p>
      </div>
    </div>
  </div>
  <div id="amenities" class="amenities container text-center">
    <h2>Thank You</h2>
    <p>Thank you for choosing Calumbuyan Point Beach Resort. We look forward to welcoming you to our family and sharing the beauty of our paradise with you.</p>
  </div>
  <!-- Contact Section -->
  <div id="contact" class="contact-form container">
    <h2 class="text-center">Contact Us</h2>
    <div class="row">
      <div class="col-md-8 offset-md-2">
        <form>
          <div class="form-row">
            <div class="form-group col-md-6">
              <label for="name">Name</label>
              <input type="text" class="form-control" id="name" placeholder="Name">
            </div>
            <div class="form-group col-md-6">
              <label for="email">Email</label>
              <input type="email" class="form-control" id="email" placeholder="Email">
            </div>
          </div>
          <div class="form-group">
            <label for="message">Message</label>
            <textarea class="form-control" id="message" rows="4" placeholder="Message"></textarea>
          </div>
          <button type="submit" class="btn btn-primary btn-block">Submit</button>
        </form>
      </div>
    </div>
    <div class="row mt-5">
      <div class="col-md-8 offset-md-2 text-center">
        <h3>Contact Information</h3>
        <p><strong>Address:</strong> Sitio Calumbuyan Palacio Farms, Santa Ana, Calatagan, Batangas, Philippines 4215</p>
        <p><strong>Phone:</strong> 0998 559 0730</p>
        <p><strong>Email:</strong> calumbuyanpoint@gmail.com</p>
        <a href="https://www.facebook.com/calumbuyanpoint" class="btn btn-primary" target="_blank">Visit our Facebook Page</a>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="footer mt-auto py-3 bg-light">
    <div class="container text-center">
      <span class="text-muted">&copy; 2024 Calumbuyan Point Resort -E.PALACIO. All rights reserved.</span>
    </div>
  </footer>

  <!-- Bootstrap JS, Popper.js, and jQuery -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
  <!-- Custom JS for image slideshow -->
  <script>
    document.addEventListener('DOMContentLoaded', function() {
      const imageContainers = document.querySelectorAll('.image-container');
      imageContainers.forEach(container => {
        const images = container.querySelectorAll('img');
        let currentIndex = 0;

        setInterval(() => {
          images[currentIndex].classList.remove('active');
          currentIndex = (currentIndex + 1) % images.length;
          images[currentIndex].classList.add('active');
        }, 3000); // Change image every 3 seconds
      });
    });
  </script>
</body>
</html>
