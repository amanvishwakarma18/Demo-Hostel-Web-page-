<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="stylesheet" href="style.css" />
      <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
      <!-- Other head content -->
  
  </head>
  <body>
    <header>
      <div class="navbar">
        <ul class="navlist">
          <div class="left"><img src="logo-removebg-preview.png" alt="" /></div>
          <div class="right">
            <li></li>
            <li><a href="#home">Home</a></li>
            <li><a href="#rooms">Rooms</a></li>
            <li><a href="#team">Team</a></li>
            <li><a href="#complaint">Complaint</a></li>
            <li><a href="#footer">Contact Us</a></li>
          </div>
        </ul>
      </div>
    </header>
    <section class="home" id="home">
      <div class="heading"><h1>Welcome to Satkar Hostel</h1></div>
      <div class="facility">
        <div class="upimg">
          <img src="img1.jpg" alt="" />
          <img src="img2.jpg" alt="" />
          <img src="img3.jpg" alt="" />
        </div>
        <div class="downimg">
          <img src="img4.jpg" alt="" />
          <img src="img5.jpg" alt="" />
          <img src="img6.jpg" alt="" />
        </div>
      </div>
    </section>

    <section class="rooms" id="rooms">
      <div class="heading"><h1>Our Rooms</h1></div>
      <div class="myrooms">
        <div class="roomimg room1"><img src="room1.jpg" alt="" /></div>
        <div class="roomimg room3"><img src="room3.jpg" alt="" /></div>
        <div class="roomimg room4"><img src="room4.jpg" alt="" /></div>
        <div class="roomimg room5"><img src="room5.jpg" alt="" /></div>
        <div class="roomimg room6"><img src="room6.jpg" alt="" /></div>
        <div class="roomimg room7"><img src="room7.jpg" alt="" /></div>
      </div>
    </section>

    <section class="team" id="team">
      <div class="heading"><h1>Our Team</h1></div>
      <div class="owner teamimg"><img src="owner.jpg" alt=""><p>Shivam Sharma (Owner)</p></div>
    <div class="allimg">
      <div class="staff1 teamimg"><img src="staff1.jpg" alt=""><p>Aloke Raghuvanshi (Warden)</p></div>
      <div class="staff2 teamimg"><img src="staff2.jpg" alt=""><p>Shiv Chouhan (Warden)</p></div>
    </div>
    </section>

    <section class="complaint" id="complaint">
      <div class="heading"><h1>Complaint</h1></div>
      <div class="form-container">
          <h2>Complaint Form</h2>
          <form action="#" method="POST">
              <div class="form-group">
                  <label for="fullname">Full Name</label>
                  <input type="text" id="fullname" name="fullname" placeholder="Enter your full name" required>
              </div>
              <div class="form-group">
                  <label for="contact">Contact Number</label>
                  <input type="tel" id="contact" name="contact" placeholder="Enter your contact number" required>
              </div>
              <div class="form-group">
                  <label for="complaint-text">Your Complaint</label>
                  <textarea id="complaint-text" name="complaint" rows="5" placeholder="Write your complaint here..." required></textarea>
              </div>
              <button type="submit">Submit Complaint</button>
          </form>
      </div>
  </section>
  

    <footer class="footer" id="footer">
      <div class="footer-container">
          <!-- About Us Section -->
          <div class="footer-section about">
              <h2>About Us</h2>
              <p>
                  We are a premier hostel providing comfortable and affordable lodging for students and travelers. Our goal is to offer a home-like experience with top-notch facilities.
              </p>
          </div>
  
          <!-- Quick Links Section -->
          <div class="footer-section quick-links">
              <h2>Quick Links</h2>
              <ul>
                  <li><a href="#home">Home</a></li>
                  <li><a href="#rooms">Our Rooms</a></li>
                  <li><a href="#mess">Mess Info</a></li>
                  <li><a href="#complaint">Complaint Form</a></li>
                  <li><a href="#contact">Contact Us</a></li>
              </ul>
          </div>
  
          <!-- Contact Information Section -->
          <div class="footer-section contact-info">
              <h2>Contact Information</h2>
              <ul>
                  <li><i class="fas fa-map-marker-alt"></i> 123 Hostel Street, City Name, Country</li>
                  <li><i class="fas fa-phone"></i> +123 456 7890</li>
                  <li><i class="fas fa-envelope"></i> satkarhostel@gmail.com</li>
              </ul>
          </div>
  
          <!-- Social Media Section -->
          <div class="footer-section social-media">
              <h2>Follow Us</h2>
              <div class="social-icons">
                  <a href="#"><i class="fab fa-facebook-f"></i></a>
                  <a href="#"><i class="fab fa-twitter"></i></a>
                  <a href="#"><i class="fab fa-instagram"></i></a>
                  <a href="#"><i class="fab fa-linkedin-in"></i></a>
              </div>
          </div>
  
          <!-- Newsletter Section -->
          <div class="footer-section newsletter">
              <h2>Newsletter Signup</h2>
              <form action="#">
                  <input type="email" placeholder="Enter your email" required>
                  <button type="submit">Subscribe</button>
              </form>
          </div>
      </div>
  
      <div class="footer-bottom">
          <p>&copy; 2024 Satkar Hostel | All Rights Reserved</p>
      </div>
  </footer>
  </body>
</html>
