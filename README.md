HTML CODE
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" >
    <meta name="viewport" 
    content="width=device-width, initial-scale=1.0" >
    <title>Document</title>
    <link rel="stylesheet" href="style.css" />
    <link
      href="https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css"
      rel="stylesheet"
    />

    
    </style>
  </head>
  <body>
    <header class="header">
      <a href="#home" class="logo">Anurag
        <span>Yadav</span>
      </a>

      <i class="bx bx-menu" id="menu-icon"></i>

      <nav class="navbar">
        <a href="#home" class="active">Home</a>
        <a href="#education">Education</a>
        <a href="#services">Services</a>
        <a href="#testimonials">Testimonials</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <section class="home" id="home">
      <div class="home-content">
        <h1>Hi, It's <span>Anurag</span></h1>
        <h3 class="text-animation">I'm a <span></span></h3>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Illum nam id
          assumenda ullam necessitatibus delectus similique, pariatur quod
          consequatur deleniti voluptate esse molestiae provident odio sequi ex
          molestias eius asperiores.
        </p>

        <div class="social-icons">
          <a href="#"><i class="bx bxl-linkedin"></i></a>
          <a href="#"><i class="bx bxl-github"></i></a>
          <a href="#"><i class="bx bxl-instagram-alt"></i></a>
          <a href="#"><i class="bx bxl-twitter"></i></a>
        </div>

        <div class="btn-group">
          <a href="#" class="btn">Hire</a>
          <a href="#contact" class="btn">Contact</a>
        </div>
      </div>
      <div class="home-image">
        <img src="image.jpg" alt="" />
      </div>
    </section>



    <!-- Education -->
    <section class="education" id="education">
      <h2 class="heading">Education</h2>

      <div class="timeline-items">


        <div class="timeline-item">
          <div class="timeline-dot"></div>
          <div class="timeline-date">2018</div>
          <div class="timeline-content">
            <h3>Class 10</h3>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo rem
              ullam non vero molestias ex! Ea, quaerat laboriosam! Fugiat hic
              impedit in? Rem quasi dolores, temporibus sunt perspiciatis nulla
              autem.
            </p>
          </div>
        </div>

        <div class="timeline-item">
          <div class="timeline-dot"></div>
          <div class="timeline-date">2020</div>
          <div class="timeline-content">
            <h3>Class 12</h3>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo rem
              ullam non vero molestias ex! Ea, quaerat laboriosam! Fugiat hic
              impedit in? Rem quasi dolores, temporibus sunt perspiciatis nulla
              autem.
            </p>
          </div>
        </div>

        <div class="timeline-item">
          <div class="timeline-dot"></div>
          <div class="timeline-date">2024</div>
          <div class="timeline-content">
            <h3>University</h3>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo rem
              ullam non vero molestias ex! Ea, quaerat laboriosam! Fugiat hic
              impedit in? Rem quasi dolores, temporibus sunt perspiciatis nulla
              autem.
            </p>
          </div>
        </div>

        <div class="timeline-item">
          <div class="timeline-dot"></div>
          <div class="timeline-date">2024</div>
          <div class="timeline-content">
            <h3>Internship</h3>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo rem
              ullam non vero molestias ex! Ea, quaerat laboriosam! Fugiat hic
              impedit in? Rem quasi dolores, temporibus sunt perspiciatis nulla
              autem.
            </p>
          </div>
        </div>
      </div>
    </section>


    <!-- SErvices -->
    <section class="services" id="services">
      <h2 class="heading">Services</h2>

      <div class="services-container">
        <div class="service-box">
          <div class="service-info">
            <h4>UI Design</h4>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum sint repellat commodi sapiente unde itaque consequuntur recusandae error qui aliquid eius, maxime reprehenderit rerum ut suscipit. Dolore velit voluptatum laboriosam.</p>

          </div>
        </div>

        <div class="service-box">
          <div class="service-info">
            <h4>Frontend Development</h4>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum sint repellat commodi sapiente unde itaque consequuntur recusandae error qui aliquid eius, maxime reprehenderit rerum ut suscipit. Dolore velit voluptatum laboriosam.</p>
            
          </div>
        </div>

        <div class="service-box">
          <div class="service-info">
            <h4>Backend Development</h4>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum sint repellat commodi sapiente unde itaque consequuntur recusandae error qui aliquid eius, maxime reprehenderit rerum ut suscipit. Dolore velit voluptatum laboriosam.</p> 
          </div>
        </div>

        <div class="service-box">
          <div class="service-info">
            <h4>AI/ML</h4>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum sint repellat commodi sapiente unde itaque consequuntur recusandae error qui aliquid eius, maxime reprehenderit rerum ut suscipit. Dolore velit voluptatum laboriosam.</p>
          </div>
        </div>
      </div>
    </section>



    <!-- Testimonials -->
    <section class="testimonials" id="testimonials">
      <div class="testimonials-box">
        <h2 class="heading">Testimonials</h2>

        <div class="wrapper">
          <div class="testimonials-item">
            <img src="1.jpeg" alt="">
            <h2>Marilyn</h2>
            <div class="rating">
              <i class='bx bxs-star' id="star"></i>
              <i class='bx bxs-star' id="star"></i>
              <i class='bx bxs-star' id="star"></i>
              <i class='bx bxs-star' id="star"></i>
              <i class='bx bxs-star' id="star"></i>
            </div>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Placeat voluptate reiciendis quaerat rem non nulla expedita nihil et minus accusantium deserunt laborum, doloremque totam autem nisi obcaecati nesciunt, sint quod!</p>
          </div>
          

          <div class="testimonials-item">
            <img src="1.jpeg" alt="">
            <h2>Marilyn</h2>
            <div class="rating">
              <i class='bx bxs-star' id="star"></i>
              <i class='bx bxs-star' id="star"></i>
              <i class='bx bxs-star' id="star"></i>
              <i class='bx bxs-star' id="star"></i>
              <i class='bx bxs-star' id="star"></i>
            </div>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Placeat voluptate reiciendis quaerat rem non nulla expedita nihil et minus accusantium deserunt laborum, doloremque totam autem nisi obcaecati nesciunt, sint quod!</p>
          </div>

          <div class="testimonials-item">
            <img src="1.jpeg" alt="">
            <h2>Marilyn</h2>
            <div class="rating">
              <i class='bx bxs-star' id="star"></i>
              <i class='bx bxs-star' id="star"></i>
              <i class='bx bxs-star' id="star"></i>
              <i class='bx bxs-star' id="star"></i>
              <i class='bx bxs-star' id="star"></i>
            </div>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Placeat voluptate reiciendis quaerat rem non nulla expedita nihil et minus accusantium deserunt laborum, doloremque totam autem nisi obcaecati nesciunt, sint quod!</p>
          </div>


        </div>
      </div>
    </section>

    <!-- Contact -->

    <section class="contact" id="contact">
      <h2 class="heading">Contact <span>Me</span></h2>

      <form action="">
        <div class="input-group">
          <div class="input-box">
            <input type="text"
            placeholder="Full Name">
            <input type="email"
            placeholder="Email">
          </div>
        
          <div class="input-box">
            <input type="number"
            placeholder="Phone Number">
            <input type="text"
            placeholder="Subject">
          </div>
        </div>
          <div class="input-group-2">
            <textarea name="" id="" cols="30"
            rows="10" placeholder="Your Message"></textarea>
            <input type="submit" value="Send Message" class="btn">
          </div>
      </form>
    </section>

    <footer class="footer">
      <div class="social">
        <a href="#"><i class="bx bxl-linkedin"></i></a>
          <a href="#"><i class="bx bxl-github"></i></a>
          <a href="#"><i class="bx bxl-instagram-alt"></i></a>
          <a href="#"><i class="bx bxl-twitter"></i></a>
      </div>

      <ul class="list">
        <li>
          <a href="#">FAQ</a>
        </li>

        <li>
          <a href="#">Services</a>
        </li>

        <li>
          <a href="#">About Me</a>
        </li>

        <li>
          <a href="#">Contact</a>
        </li>

        <li>
          <a href="#">Testimonials</a>
        </li>
      </ul>
      <p class="copyright">
        © Anurag Yadav | All Rights Reserved
      </p>
    </footer>
    <sript src="script.js"></sript>
  </body>
</html>

