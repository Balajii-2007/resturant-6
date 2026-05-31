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
  <title>Bella Terra — Administration</title>
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
      <li><a href="index.html">Home</a></li>
      <li><a href="menu.html">Menu</a></li>
      <li><a href="administration.html" class="active">Administration</a></li>
      <li><a href="contact.html">Contact</a></li>
    </ul>
  </nav>

  <section class="page-header" data-bg-text="Team">
    <span class="section-label">The People</span>
    <h1>Administration</h1>
    <p>The artisans and stewards who make every evening exceptional.</p>
  </section>

  <section class="admin-section">
    <div class="team-grid">

      <div class="team-card">
        <div class="team-img" style="background-image:url('https://images.unsplash.com/photo-1577219491135-ce391730fb2c?w=500&q=80')"></div>
        <div class="team-body">
          <span class="team-role-tag">Head Chef</span>
          <div class="team-name">Mr. Matteo Rinaldi</div>
          <div class="team-divider"></div>
          <p class="team-desc">Trained in Florence and Bologna. Leads the kitchen with 28 years of craft and passion for seasonal Italian cooking.</p>
        </div>
      </div>

      <div class="team-card">
        <div class="team-img" style="background-image:url('https://images.unsplash.com/photo-1559628376-f3fe5f782a2e?w=500&q=80')"></div>
        <div class="team-body">
          <span class="team-role-tag">Sous Chef</span>
          <div class="team-name">Ms. Priya Venkat</div>
          <div class="team-divider"></div>
          <p class="team-desc">Manages daily prep, quality standards, and station coordination with precision and creativity.</p>
        </div>
      </div>

      <div class="team-card">
        <div class="team-img" style="background-image:url('https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?w=500&q=80')"></div>
        <div class="team-body">
          <span class="team-role-tag">General Manager</span>
          <div class="team-name">Mr. Rahul Krishnan</div>
          <div class="team-divider"></div>
          <p class="team-desc">Orchestrates the guest experience from reservation to farewell. Every detail, every evening.</p>
        </div>
      </div>

      <div class="team-card">
        <div class="team-img" style="background-image:url('https://images.unsplash.com/photo-1595273670150-bd0c3c392e46?w=500&q=80')"></div>
        <div class="team-body">
          <span class="team-role-tag">Finance Director</span>
          <div class="team-name">Ms. Ananya Iyer</div>
          <div class="team-divider"></div>
          <p class="team-desc">Oversees financial planning, vendor relations, and sustainable sourcing budgets.</p>
        </div>
      </div>

      <div class="team-card">
        <div class="team-img" style="background-image:url('https://images.unsplash.com/photo-1534308143481-c55f00be8bd7?w=500&q=80')"></div>
        <div class="team-body">
          <span class="team-role-tag">Head Sommelier</span>
          <div class="team-name">Mr. Vikram Nair</div>
          <div class="team-divider"></div>
          <p class="team-desc">Curates our Italian and Indian wine list. Expert in pairing regional varietals with Chef Matteo's tasting menu.</p>
        </div>
      </div>

      <div class="team-card">
        <div class="team-img" style="background-image:url('https://images.unsplash.com/photo-1551836022-4c4c79ecde51?w=500&q=80')"></div>
        <div class="team-body">
          <span class="team-role-tag">Events Manager</span>
          <div class="team-name">Ms. Divya Srinivasan</div>
          <div class="team-divider"></div>
          <p class="team-desc">Designs bespoke private dining and corporate events. From intimate dinners to grand celebrations.</p>
        </div>
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


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Bella Terra — Menu</title>
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
      <li><a href="index.html">Home</a></li>
      <li><a href="menu.html" class="active">Menu</a></li>
      <li><a href="administration.html">Administration</a></li>
      <li><a href="contact.html">Contact</a></li>
    </ul>
  </nav>

  <section class="page-header" data-bg-text="Menu">
    <span class="section-label">Our Offerings</span>
    <h1>The Menu</h1>
    <p>Crafted daily with the season's finest produce and old-world technique.</p>
  </section>

  <section class="menu-section">
    <div class="menu-category-label">
      <span>Chef's Selection — 12 Dishes</span>
    </div>
    <div class="menu-grid">

      <div class="menu-card">
        <div class="menu-img" style="background-image:url('https://images.unsplash.com/photo-1574071318508-1cdbab80d002?w=500&q=80')">
          <span class="menu-img-price">₹699</span>
        </div>
        <div class="menu-body">
          <div class="menu-name">Margherita Verace</div>
          <div class="menu-desc">San Marzano tomato, buffalo mozzarella, fresh basil</div>
          <button class="btn-order">Add to Order</button>
        </div>
      </div>

      <div class="menu-card">
        <div class="menu-img" style="background-image:url('https://images.unsplash.com/photo-1598103442097-8b74394b95c9?w=500&q=80')">
          <span class="menu-img-price">₹799</span>
        </div>
        <div class="menu-body">
          <div class="menu-name">Pollo alla Brace</div>
          <div class="menu-desc">Wood-grilled chicken, rosemary jus, roasted garlic</div>
          <button class="btn-order">Add to Order</button>
        </div>
      </div>

      <div class="menu-card">
        <div class="menu-img" style="background-image:url('https://images.unsplash.com/photo-1555396273-367ea4eb4db5?w=500&q=80')">
          <span class="menu-img-price">₹649</span>
        </div>
        <div class="menu-body">
          <div class="menu-name">Penne all'Arrabbiata</div>
          <div class="menu-desc">Spiced tomato, capers, Sicilian chilli, pecorino</div>
          <button class="btn-order">Add to Order</button>
        </div>
      </div>

      <div class="menu-card">
        <div class="menu-img" style="background-image:url('https://images.unsplash.com/photo-1612874742237-6526221588e3?w=500&q=80')">
          <span class="menu-img-price">₹749</span>
        </div>
        <div class="menu-body">
          <div class="menu-name">Spaghetti Carbonara</div>
          <div class="menu-desc">Guanciale, egg yolk, pecorino, black pepper</div>
          <button class="btn-order">Add to Order</button>
        </div>
      </div>

      <div class="menu-card">
        <div class="menu-img" style="background-image:url('https://images.unsplash.com/photo-1467003909585-2f8a72700288?w=500&q=80')">
          <span class="menu-img-price">₹1099</span>
        </div>
        <div class="menu-body">
          <div class="menu-name">Salmone alla Griglia</div>
          <div class="menu-desc">Grilled salmon, lemon butter, caperberry, dill</div>
          <button class="btn-order">Add to Order</button>
        </div>
      </div>

      <div class="menu-card">
        <div class="menu-img" style="background-image:url('https://images.unsplash.com/photo-1588166524941-3bf61a9c41db?w=500&q=80')">
          <span class="menu-img-price">₹799</span>
        </div>
        <div class="menu-body">
          <div class="menu-name">Pollo Makhani</div>
          <div class="menu-desc">Chef's cross-cultural signature, slow-cooked butter sauce</div>
          <button class="btn-order">Add to Order</button>
        </div>
      </div>

      <div class="menu-card">
        <div class="menu-img" style="background-image:url('https://images.unsplash.com/photo-1565299624946-b28f40a0ae38?w=500&q=80')">
          <span class="menu-img-price">₹849</span>
        </div>
        <div class="menu-body">
          <div class="menu-name">Pizza Napoletana</div>
          <div class="menu-desc">Anchovies, olives, capers, tomato, oregano</div>
          <button class="btn-order">Add to Order</button>
        </div>
      </div>

      <div class="menu-card">
        <div class="menu-img" style="background-image:url('https://images.unsplash.com/photo-1547592180-85f173990554?w=500&q=80')">
          <span class="menu-img-price">₹699</span>
        </div>
        <div class="menu-body">
          <div class="menu-name">Pollo Tikka</div>
          <div class="menu-desc">Tandoor-kissed, yoghurt marinade, mint chutney</div>
          <button class="btn-order">Add to Order</button>
        </div>
      </div>

      <div class="menu-card">
        <div class="menu-img" style="background-image:url('https://images.unsplash.com/photo-1504674900247-0877df9cc836?w=500&q=80')">
          <span class="menu-img-price">₹1499</span>
        </div>
        <div class="menu-body">
          <div class="menu-name">Bistecca Fiorentina</div>
          <div class="menu-desc">T-bone, rosemary salt, Tuscan olive oil, arugula</div>
          <button class="btn-order">Add to Order</button>
        </div>
      </div>

      <div class="menu-card">
        <div class="menu-img" style="background-image:url('https://images.unsplash.com/photo-1563379091339-03246963d96c?w=500&q=80')">
          <span class="menu-img-price">₹599</span>
        </div>
        <div class="menu-body">
          <div class="menu-name">Rigatoni al Forno</div>
          <div class="menu-desc">Baked with béchamel, ragù, and aged provolone</div>
          <button class="btn-order">Add to Order</button>
        </div>
      </div>

      <div class="menu-card">
        <div class="menu-img" style="background-image:url('https://images.unsplash.com/photo-1569050467447-ce54b3bbc37d?w=500&q=80')">
          <span class="menu-img-price">₹399</span>
        </div>
        <div class="menu-body">
          <div class="menu-name">Tiramisù della Casa</div>
          <div class="menu-desc">Mascarpone, espresso, Savoiardi, dark cocoa</div>
          <button class="btn-order">Add to Order</button>
        </div>
      </div>

      <div class="menu-card">
        <div class="menu-img" style="background-image:url('https://images.unsplash.com/photo-1565958011703-44f9829ba187?w=500&q=80')">
          <span class="menu-img-price">₹249</span>
        </div>
        <div class="menu-body">
          <div class="menu-name">Pane all'Aglio</div>
          <div class="menu-desc">Sourdough, roasted garlic butter, parsley, sea salt</div>
          <button class="btn-order">Add to Order</button>
        </div>
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
