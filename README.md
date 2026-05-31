# Ex.06 Restuarant Website
## Date:

## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Bella Terra — Home</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;0,900;1,400;1,700&family=Cormorant+Garamond:ital,wght@0,300;0,400;0,500;1,300;1,400&family=Josefin+Sans:wght@300;400;600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="css/style.css"/>
</head>
<body>

  <nav class="navbar">
    <div class="nav-brand" onclick="location.href='index.html'">
      <span class="nav-brand-main">Bella Terra</span>
      <span class="nav-brand-sub">Fine Dining · Est. 1996</span>
    </div>
    <ul class="nav-links">
      <li><a href="index.html" class="active">Home</a></li>
      <li><a href="menu.html">Menu</a></li>
      <li><a href="administration.html">Administration</a></li>
      <li><a href="contact.html">Contact</a></li>
    </ul>
  </nav>

  <!-- HERO -->
  <section class="hero">
    <div class="hero-left">
      <div class="hero-img"></div>
      <div class="hero-img-overlay"></div>
      <div class="hero-stamp">
        <span>Est.</span>
        <span>1996</span>
      </div>
    </div>
    <div class="hero-right">
      <div class="hero-content">
        <span class="hero-eyebrow">Chennai's finest Italian table</span>
        <h1 class="hero-title">Where Every<br>Plate Tells a<br><em>Story</em></h1>
        <div class="hero-divider"></div>
        <p class="hero-sub">Rooted in old-world Italian tradition, grown in the heart of Chennai. Seasonal produce. Open fire. Unhurried hospitality.</p>
        <div class="hero-actions">
          <a href="menu.html" class="btn-fill"><span>Explore Menu</span></a>
          <a href="contact.html" class="btn-ghost">Reserve a Table</a>
        </div>
      </div>
    </div>
  </section>

  <!-- FEATURES -->
  <div class="features-strip">
    <div class="feat">
      <div class="feat-icon">🔥</div>
      <div class="feat-text">
        <h3>Wood-Fired Ovens</h3>
        <p>Imported Neapolitan clay. 450°C perfection.</p>
      </div>
    </div>
    <div class="feat">
      <div class="feat-icon">🌿</div>
      <div class="feat-text">
        <h3>Farm-to-Table</h3>
        <p>Sourced within 100km of our kitchen.</p>
      </div>
    </div>
    <div class="feat">
      <div class="feat-icon">🕯</div>
      <div class="feat-text">
        <h3>Private Dining</h3>
        <p>Intimate rooms for up to 20 guests.</p>
      </div>
    </div>
  </div>

  <!-- STORY -->
  <section class="story">
    <div class="story-text">
      <div class="ornament">
        <div class="ornament-line"></div>
        <span class="ornament-text">Our Heritage</span>
      </div>
      <h2>Born in a <em>Courtyard</em><br>Kitchen</h2>
      <p>Bella Terra began as a small courtyard trattoria in 1996. Chef Matteo Rinaldi brought his grandmother's Florentine recipes to Chennai, blending Italian soul with local spice. What started as a 12-seat restaurant is now the city's most celebrated dining destination.</p>
      <p>Our philosophy is simple: the best ingredients need the least intervention. Everything is made in-house — from our sourdough to our pasta, our sauces to our gelato.</p>
      <a href="administration.html" class="btn-ghost">Meet the Team</a>
    </div>
    <div class="story-image">
      <div class="story-image-main"></div>
      <div class="story-image-badge">28 years of flavor</div>
    </div>
  </section>

  <!-- TESTIMONIALS -->
  <section class="testimonials">
    <div class="testimonials-header">
      <span class="section-label" style="color:var(--gold);text-align:center;display:block;">Guest Voices</span>
      <h2>Memories Made at the Table</h2>
      <p>Every evening is a story worth telling.</p>
    </div>
    <div class="testimonials-grid">
      <div class="t-card">
        <p>The tagliatelle al ragù transported me straight to Bologna. The depth of flavor, the perfect al dente bite — I've been coming back every month since.</p>
        <span class="t-card-author">— Kavitha R., Chennai</span>
      </div>
      <div class="t-card">
        <p>We celebrated our anniversary here and the evening was flawless. The sommelier's wine pairing was inspired, and the tiramisu was the finest I've ever had.</p>
        <span class="t-card-author">— Arjun & Meera S.</span>
      </div>
      <div class="t-card">
        <p>The wood-fired pizza is a masterpiece. Blistered crust, bright tomato, fresh buffalo mozzarella. It's the kind of simplicity that takes decades to perfect.</p>
        <span class="t-card-author">— Rajan T., Bangalore</span>
      </div>
    </div>
  </section>

  <footer class="footer">
    <div class="footer-brand">Bella Terra</div>
    <div class="footer-text">&copy; 2025 Bella Terra Fine Dining &mdash; Designed by <strong>Parani Bala M</strong></div>
    <div class="footer-ornament">❧</div>
  </footer>

</body>
</html>

~~~
## OUTPUT:
<img width="1600" height="868" alt="resturant-1" src="https://github.com/user-attachments/assets/8b1877b4-cf44-416e-8f7c-5ca0d633f14b" />
<img width="1600" height="819" alt="resturant-2" src="https://github.com/user-attachments/assets/a5cb80bd-40cf-4760-b2b6-f67337e14cf4" />
<img width="1600" height="869" alt="resturant-3" src="https://github.com/user-attachments/assets/3d40c331-5743-4f87-abb5-38a8e36ebec9" />


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
