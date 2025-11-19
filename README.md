# POE-Braai-website
this is a website for my braai restaurant, i created it to make things more convenient for chisanyama lovers
<!doctype html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Home - Fire Feast</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <header>
    <section class="hero">
      <div class="hero-content">
        <h1>Fire Feast</h1>
        <h2>Where Every Bite is Lit!</h2>
      </div>
    </section>
    <nav class="navigation">
      <ul>
        <li><a href="home.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="gallery.html">Gallery</a></li>
        <li><a href="news.html">News</a></li>
        <li><a href="contact.html">Contact us</a></li>
      </ul>
      <section class="search-bar">
        <input type="text" id="searchBar" placeholder="Search combos, meals, or drinks...">
        <button id="searchBtn">Search</button>
      </section>
    </nav>
  </header>
  
  <main class="welcome">
    <h1>About Us</h1>
    <h3>We are proudly South African Chisanyama restaurant serving mouth-watering grilled meat,</h3>
    <h3>traditional sides and a lively atmosphere. Braaiing isn't just cooking, it's our way of celebrating life!</h3>

    <h2>Our Services</h2>
    <ol>
      <li>Dining Experience</li>
      <li>Order collection - call to place your order and collect at your convenience</li>
      <li>Event catering - We bring you the Chisanyama experience.</li>
    </ol>
  </main>
  
  <footer>
    <p>&copy; ST10485724 | </p>
	<div id="footer-date-time"></div>
  </footer>

<script src="javascript/script.js"></script>
  <!-- Link to external JS -->
</body>
</html>

<!doctype html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Gallery page</title>
</head>
<body>
  <header>
    <nav>
      <div align="left">
        <img src="Images/a.JPG" style="width:300px; height:300px">
        <img src="Images/b.JPG" style="width:300px; height:300px">
        <img src="Images/e.JPG" style="width:300px; height:300px">
        <img src="Images/f.JPG" style="width:300px; height:300px">
        <img src="Images/c.PNG" style="width:300px; height:300px">
		<img src="Images/c.JPG" style="width:300px; height:300px">
		<img src="Images/d.JPG" style="width:300px; height:300px">
		<img src="Images/h.JPG" style="width:300px; height:300px">
		<img src="Images/j.JPG" style="width:300px; height:300px">
      </div>
      <div>
        <ul>
          <li><a href="home.html">Home</a></li>
          <li><a href="menu.html">Menu</a></li>
          <li><a href="gallery.html">Gallery</a></li>
          <li><a href="news.html">News</a></li>
          <li><a href="contact.html">Contact</a></li>
        </ul>
      </div>
    </nav>
  </header>
  <main>
    <h1> </h1>
    <h2>  </h2>
    <video width="100%" height="500" controls>
      <source src="Images/aa.mp4" type="video/mp4">
    </video>
  </main>

  <footer>
    <p>&copy; ST10485724</p>
	<div id="footer-date-time"></div>
  </footer>
  
  <script src="javascript/script.js"></script>

</body>
</html>

<!doctype html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Menu - Fire Feast</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body class="menu-page">
  <header>
    <nav class="navigation">
      <div align="left">
        <img src="Images/f.JPG" style="width:250px; height:250px">
      </div>
      <ul>
        <li><a href="home.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="gallery.html">Gallery</a></li>
        <li><a href="news.html">News</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <h1>Chisa Choices</h1>
    <p><strong>Meat selection:</strong></p>
    <p>Beef, Boerwors, Chicken, Ribs</p> 
    <p><strong>Sides served in sizes sml, med, lrg:</strong></p>
    <p>Chakalaka, Coleslaw, Salsa, Atchaar, Spinach</p>
    
    <h1 class="combo-title">Feast Mode — Combos</h1>
    <section id="combos">
      <article class="combo-item">
        <div class="combo-content">
          <h2>The Braiwan Classic</h2>
          <ul>
            <li>2 Boerewors sausages</li>
            <li>1/4 Chicken (flame-grilled)</li>
            <li>Pap & chakalaka</li>
            <li>Side of coleslaw</li>
          </ul>
          <p><strong>Price:</strong> R150</p>
        </div>
        <div class="combo-image">
          <img src="Images/d.JPG" style="width:200px; height:200px;" alt="Braiwan Classic">
        </div>
      </article>

      <article class="combo-item">
        <div class="combo-content">
          <h2>Meat Lovers’ Feast</h2>
          <ul>
            <li>Steak</li>
            <li>Pork ribs (4 pieces)</li>
            <li>Grilled wors</li>
            <li>Chips or pap</li>
            <li>Tomato relish</li>
          </ul>
          <p><strong>Price:</strong> R250</p>
        </div>
        <div class="combo-image">
          <img src="Images/j.JPG" style="width:200px; height:200px;" alt="Meat Lovers Feast">
        </div>
      </article>

      <article class="combo-item">
        <div class="combo-content">
          <h2>The Chisa Experience</h2>
          <ul>
            <li>Grilled beef short ribs</li>
            <li>Chicken wings (6)</li>
            <li>Traditional pap & spinach</li>
            <li>Salsa / chakalaka</li>
            <li>Choice of soft drink</li>
          </ul>
          <p><strong>Price:</strong> R200</p>
        </div>
        <div class="combo-image">
          <img src="Images/h.JPG" style="width:200px; height:200px;" alt="Chisa Experience">
        </div>
      </article>
    </section>
  </main>

  <footer>
    <p>&copy; ST10485724</p>
	<div id="footer-date-time"></div>
  </footer>

  <script src="javascript/script.js"></script>

</body>
</html>

<!doctype html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>News - Fire Feast</title>
  <link rel="stylesheet" href="css/style.css">
  <style>
    /* General styling for the news sections */
    .news-section {
      margin: 30px auto;
      max-width: 900px;
      text-align: center;
    }

    /* Title styling for the sections */
    .news-section h1 {
      margin-bottom: 20px;
      color: #FF7E00; /* Light orange */
      font-size: 2rem;
    }

    /* Styling for individual news cards */
    .news-card {
      display: inline-block;
      width: 300px; 
      background-color: #fffbea; /* Light cream */
      margin: 15px;
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 6px 15px rgba(0, 0, 0, 0.2);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .news-card:hover {
      transform: translateY(-10px);
      box-shadow: 0 12px 20px rgba(0, 0, 0, 0.3);
    }

    .news-card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 10px;
    }

    .news-card p {
      color: #2b1d0e; /* Dark brown text */
      margin-top: 15px;
    }

    .news-card ul {
      list-style: none;
      padding: 0;
      margin: 10px 0;
    }

    .news-card li {
      font-size: 1.1rem;
      line-height: 1.6;
    }

    /* Responsiveness */
    @media (max-width: 768px) {
      .news-card {
        width: 45%; /* Two cards per row */
      }
    }

    @media (max-width: 480px) {
      .news-card {
        width: 100%; /* Full-width cards on small screens */
      }
    }
  </style>
</head>
<body>
  <header>
    <nav class="navigation">
      <ul>
        <li><a href="home.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="gallery.html">Gallery</a></li>
        <li><a href="news.html">News</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section class="news-section">
      <h1>What we have been up to</h1>
      <!-- News card for past events -->
      <div class="news-card">
        <img src="Images/c.PNG" alt="Youth Day Celebration">
        <p><strong>Youth Day Celebration:</strong> Partnered with Amber & Oak cafe to give free hot beverages and wors rolls. Youth volunteers helped serve and create a fun, community spirit.</p>
      </div>
	  <div class="news-card">
        <img src="Images/g.JPG" alt="Heritage Day Celebration">
        <p><strong>Heritage Day Celebration:</strong> We had a great time celebrating the nations diverse cultures, with a perfomance from our local dj Wesley Keys and 20% off meals topped with a free drink.</p>
      </div>
    </section>

    <section class="news-section">
      <h1>What's to come!</h1>
      <!-- News card for upcoming events -->
      <div class="news-card">
        <img src="Images/k.JPG" alt="Black Friday Deals">
        <p><strong>Black Friday Deals:</strong> Get ready for amazing deals this Black Friday! Huge discounts on meals and special combo offers! Don't miss out on the savings.</p>
      </div>
      <div class="news-card">
        <img src="Images/m.JPG" alt="16th December Event">
        <p><strong>16th December Event:</strong> Join us for an exciting event to celebrate the festive season. Live music, great food, and a lively atmosphere. Be there!</p>
      </div>
    </section>
  </main>

  <footer>
    <p>&copy; ST10485724</p>
	<div id="footer-date-time"></div>
  </footer>
  
  <script src="javascript/script.js"></script>

</body>
</html>

<!doctype html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contact - Fire Feast</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <header>
    <nav class="navigation">
      <ul>
        <li><a href="home.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="gallery.html">Gallery</a></li>
        <li><a href="news.html">News</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <h1>Contact</h1>
	<h3> Call the number below to place your order:</h3>
    <p>Cell no: <a href="tel:0115002469">011 500 2469</a></p>
	
    <p>Whatsapp no: <a href="cell:0614458169">061 445 8169</a></p>
    <p>Email: <a href="mailto:firefeast25@gmail.com">keneilwemositi23@gmail.com</a></p>

    <h2>Our Location</h2>
    <iframe src="https://www.google.com/maps/embed?pb=!1m23!1m12!1m3!1d114564.06275177006!2d27.951487002043933!3d-26.192547931527024!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!4m8!3e6!4m0!4m5!1s0x1e950b9300000001%3A0x335d35f228da3ccd!2sBraamfontein%20Centre%2C%2023%20Jorissen%20St%2C%20Braamfontein%2C%20Johannesburg%2C%202017%2C%20South%20Africa!3m2!1d-26.192821199999997!2d28.0339195!5e0!3m2!1sen!2sie!4v1754483541549!5m2!1sen!2sie"
      width="350" height="200" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

    <h2>Operating Hours</h2>
    <ul>
      <li>Weekdays: 13:00-21:00</li>
      <li>Saturdays: 12:00-22:30</li>
      <li>Sundays: 12:00-17:00</li>
    </ul>
  </main>

  <footer>
    <p>&copy; ST10485724</p>
	<div id="footer-date-time"></div>
  </footer>
  
  <script src="javascript/script.js"></script>

</body>
</html>

 /* Global styles */
body {
  font-family: 'Arial', sans-serif;
  background-color: #FFCC80; /* Light Orange */
  color: #333; /* Dark text for readability */
  line-height: 1.0;
}

/* Header, Navigation & Footer */
header, footer {
  background-color: #FFF5E1; /* Cream White */
}

footer {
  color: #FF7E00; /* Orange text for footer */
}

/* Hero Section */
.hero {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    text-align: center;
    padding: 50px;
    border-bottom-left-radius: 20px;
    border-bottom-right-radius: 20px;
    margin-bottom: 30px;
    flex-wrap: wrap;
    background: linear-gradient(rgba(5,68,94,0.6), rgba(5,68,94,0.2)),
                url("../Images/i.JPG");
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    min-height: 60vh;
}

.hero-content {
    flex: 1;
    color: #fff;
    text-align: center;
    z-index: 2;
}

.hero-content h1 {
    font-size: 3.2rem;
    margin-bottom: 15px;
    color: #fff;
    text-shadow: 2px 2px 6px rgba(0,0,0,0.3);
}

.hero-content h2 {
    font-size: 1.6rem;
    color: #2b1d0e;
    font-weight: 500;
    background: rgba(255,255,255,0.3);
    display: inline-block;
    padding: 5px 12px;
    border-radius: 8px;
}
.search-bar {
    display: inline-flex;
    align-items: center;
    margin-top: 20px;
    position: absolute;
    top: 20px;
    right: 20px;
}

.search-bar input {
    padding: 10px;
    border-radius: 20px;
    border: 2px solid #FF7E00; /* Matching your theme */
    font-size: 1rem;
}

.search-bar button {
    padding: 10px 15px;
    border-radius: 20px;
    background-color: #FF7E00;
    color: white;
    border: none;
    cursor: pointer;
    transition: background-color 0.3s;
}

.search-bar button:hover {
    background-color: #FFA500;
}


/* Navigation */
.navigation {
  background-color: #FFF5E1; /* cream white */
  padding: 15px 0;
  text-align: center;
}

.navigation ul {
  list-style: none;
  display: flex; /* Makes the list horizontal */
  justify-content: center;
  gap: 20px; /* Space between the items */
  padding: 0;
  margin: 0;
}

.navigation a {
  color: #FF7E00; /* light orange */
  text-decoration: none;
  font-weight: bold;
  padding: 10px 20px;
  border-radius: 5px;
  background-color: #FFF5E1; /* cream white */
  transition: all 0.3s ease;
}

.navigation a:hover {
  background-color: #FF7E00; /* orange */
  color: white;
}

// Wait until DOM is fully loaded
document.addEventListener("DOMContentLoaded", function() {

  /* ============================
      1. SEARCH FUNCTIONALITY
     ============================ */
  document.getElementById("searchBtn").addEventListener("click", function() {
    const searchTerm = document.getElementById("searchBar").value.toLowerCase();
    const comboArticles = document.querySelectorAll("#combos article");

    comboArticles.forEach(article => {
        const title = article.querySelector("h2").textContent.toLowerCase();
        if (title.includes(searchTerm)) {
            article.style.display = "";
        } else {
            article.style.display = "none";
        }
    });
  });

  /* ============================
         2. GALLERY LIGHTBOX
     ============================ */
  const galleryImages = document.querySelectorAll(".gallery-images img");

  galleryImages.forEach(img => {
    img.addEventListener("click", function() {
      const lightbox = document.createElement("div");
      lightbox.id = "lightbox";
      Object.assign(lightbox.style, {
        position: "fixed",
        top: "0",
        left: "0",
        width: "100%",
        height: "100%",
        background: "rgba(0,0,0,0.8)",
        display: "flex",
        justifyContent: "center",
        alignItems: "center",
        zIndex: "1000",
        cursor: "pointer"
      });

      const imgClone = img.cloneNode();
      imgClone.style.width = "80%";
      imgClone.style.maxWidth = "800px";
      imgClone.style.borderRadius = "10px";

      lightbox.appendChild(imgClone);
      document.body.appendChild(lightbox);

      lightbox.addEventListener("click", function() {
        document.body.removeChild(lightbox);
      });
    });
  });

  /* ============================
        3. FORM VALIDATION
     ============================ */

  function validateForm(formId) {
    const form = document.getElementById(formId);
    if (!form) return;

    form.addEventListener("submit", function(e) {
      e.preventDefault();

      const name = form.querySelector("#name")?.value.trim() || "";
      const email = form.querySelector("#email")?.value.trim() || "";
      const phone = form.querySelector("#phone")?.value.trim() || "";
      const message = form.querySelector("#message")?.value.trim() || "";

      let errors = [];

      if (name.length < 2) errors.push("Name must be at least 2 characters.");
      if (!email.includes("@")) errors.push("Email is invalid.");
      if (!/^\d{10,12}$/.test(phone.replace(/\D/g, ""))) errors.push("Phone number is invalid (10-12 digits).");
      if (message.length < 10) errors.push("Message must be at least 10 characters.");

      if (errors.length > 0) {
        alert(errors.join("\n"));
        return;
      }

      alert("Form submitted successfully!");
      form.reset();
    });
  }

  // Apply to contact & enquiry forms
  validateForm("contactForm");
  validateForm("enquiryForm");

  /* ============================
        4. ACCORDION/TABS (OPTIONAL)
     ============================ */
  const comboArticles = document.querySelectorAll("#combos article");

  comboArticles.forEach(article => {
    const title = article.querySelector("h2");
    const details = Array.from(article.querySelectorAll("ul, p"));

    // Initially hide details
    details.forEach(d => d.style.display = "none");

    title.style.cursor = "pointer";

    title.addEventListener("click", () => {
      details.forEach(d => {
        d.style.display = d.style.display === "none" ? "block" : "none";
      });
    });
  });

  /* ============================
        5. DATE AND TIME (Footer)
     ============================ */
  function updateDateTime() {
    const footer = document.getElementById('footer-date-time');
    const now = new Date();

    const formattedDateTime = now.toLocaleString('en-US', {
      weekday: 'long',
      year: 'numeric',
      month: 'long',
      day: 'numeric',
      hour: 'numeric',
      minute: 'numeric',
      second: 'numeric',
      hour12: true
    });

    console.log(formattedDateTime); // This will log the date to the console to test if it's working
    footer.textContent = `Current Date and Time: ${formattedDateTime}`;
  }

  setInterval(updateDateTime, 1000); // Update every second
  updateDateTime(); // Initial call to set the time immediately

}); // End of DOMContentLoaded
