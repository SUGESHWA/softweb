# Ex.07 Restuarant Website
## Date:12/11/25 

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
```
admin.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <title>SpiceGarden - Administration</title>
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="site">
    <header class="header">
      <div class="brand">SpiceGarden</div>
      <nav>
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="admin.html" class="active">Administration</a>
        <a href="contact.html">Contact Us</a>
      </nav>
    </header>

    <section class="section">
      <h2 style="color:var(--accent)">Our Team</h2>
      <p class="subtitle">Meet the people who make SpiceGarden run.</p>

      <div class="staff-grid" style="margin-top:14px">
        <div class="staff">
          <img src="kumar.jpg" alt="Staff 1">
          <h5>Mr. R. Kumar</h5>
          <span>Proprietor</span>
        </div>

        <div class="staff">
          <img src="anjali rao.jpg" alt="Staff 2">
          <h5>Ms. Anjali Rao</h5>
          <span>Head Chef</span>
        </div>

        <div class="staff">
          <img src="venkatesh.jpg" alt="Staff 3">
          <h5>Mr. S. Venkatesh</h5>
          <span>Manager</span>
        </div>

        <div class="staff">
          <img src="meena.jpg" alt="Staff 4">
          <h5>Ms. Meena</h5>
          <span>Accounts</span>
        </div>

        <div class="staff">
          <img src="arjun.jpg" alt="Staff 5">
          <h5>Mr. Arjun</h5>
          <span>Floor Supervisor</span>
        </div>

        <div class="staff">
          <img src="latha.jpg" alt="Staff 6">
          <h5>Ms. Latha</h5>
          <span>PR & Events</span>
        </div>
      </div>
    </section>

    <footer class="footer">
      <div class="left">Color Scheme: Charcoal / Coral / Cream</div>
      <div class="right">Designed by Jothimani P</div>
    </footer>
  </div>
</body>
</html>


```
contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <title>SpiceGarden - Contact Us</title>
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="site">
    <header class="header">
      <div class="brand">SpiceGarden</div>
      <nav>
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="admin.html">Administration</a>
        <a href="contact.html" class="active">Contact Us</a>
      </nav>
    </header>

    <section class="section">
      <h2 style="color:var(--accent)">Contact Us</h2>
      <p class="subtitle">We’d love to hear from you — reservations, feedback, or catering requests.</p>

      <div class="contact-box" style="margin-top:14px">
        <div class="contact-info">
          <h4 style="margin-bottom:8px">Address</h4>
          <p>SpiceGarden Restaurant, No: 12, Main Road, Vadalur - 607303, Tamil Nadu, India</p>

          <h4 style="margin-top:12px;margin-bottom:8px">Phone</h4>
          <p>+91 98765 43210</p>

          <h4 style="margin-top:12px;margin-bottom:8px">Email</h4>
          <p>reservations@spicegarden.example</p>
        </div>

        <div class="contact-info" style="flex:1;">
          <h4 style="margin-bottom:8px">Opening Hours</h4>
          <p>Mon - Sun: 10:00 AM - 11:00 PM</p>

          <h4 style="margin-top:12px;margin-bottom:8px">Reservation</h4>
          <p>Call or email us to reserve a table for parties of any size.</p>
        </div>
      </div>
    </section>

    <footer class="footer">
      <div class="left">Color Scheme: Charcoal / Coral / Cream</div>
      <div class="right">Designed by Jothimani P</div>
    </footer>
  </div>
</body>
</html>

```
index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <title>SpiceGarden - Home</title>
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="site">
    <header class="header">
      <div class="brand">SpiceGarden</div>
      <nav>
        <a href="index.html" class="active">Home</a>
        <a href="menu.html">Menu</a>
        <a href="admin.html">Administration</a>
        <a href="contact.html">Contact Us</a>
      </nav>
    </header>

    <section class="hero">
      <div class="hero-left">
        <div class="title">WELCOME TO SPICEGARDEN</div>
        <div class="subtitle">Authentic regional flavors — fresh ingredients — cozy ambience</div>
        <button class="cta" onclick="location.href='menu.html'">Explore Menu</button>
      </div>
      <div class="banner">
        <!-- Replace banner.jpg with your chosen image -->
        <img src="banner.jpg" alt="Banner">
      </div>
    </section>

    <section class="section">
      <h3 style="color:var(--accent); margin-bottom:10px">About Us</h3>
      <p style="color:var(--muted); line-height:1.6">
        SpiceGarden is a family-owned restaurant dedicated to serving traditional recipes with modern presentation.
        We use locally sourced ingredients and prepare dishes with care to give you a delightful dining experience.
      </p>
    </section>

    <footer class="footer">
      <div class="left">Color Scheme: Charcoal / Coral / Cream</div>
      <div class="right">Designed by Jothimani P</div>
    </footer>
  </div>
</body>
</html>

```
menu.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <title>SpiceGarden - Menu</title>
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="site">
    <header class="header">
      <div class="brand">SpiceGarden</div>
      <nav>
        <a href="index.html">Home</a>
        <a href="menu.html" class="active">Menu</a>
        <a href="admin.html">Administration</a>
        <a href="contact.html">Contact Us</a>
      </nav>
    </header>

    <section class="section">
      <h2 style="color:var(--accent)">Our Menu</h2>
      <p class="subtitle">Twelve popular items — click to view details (placeholder)</p>

      <div class="grid">
        <div class="card">
          <img src="dish1.jpg" alt="Dish 1">
          <h4>Masala Dosa</h4>
          <p>Thin crispy dosa served with potato masala and chutneys.</p>
        </div>

        <div class="card">
          <img src="dish2.jpg" alt="Dish 2">
          <h4>Chicken Chettinad</h4>
          <p>Spicy Chettinad-style chicken curry cooked with authentic spices.</p>
        </div>

        <div class="card">
          <img src="dish3.jpg" alt="Dish 3">
          <h4>Paneer Butter Masala</h4>
          <p>Soft cottage cheese cubes in a rich creamy tomato gravy.</p>
        </div>

        <div class="card">
          <img src="dish4.jpg" alt="Dish 4">
          <h4>Fish Fry</h4>
          <p>Marinated fish fillet shallow-fried to golden perfection.</p>
        </div>

        <div class="card">
          <img src="dish5.jpg" alt="Dish 5">
          <h4>Biryani (Veg)</h4>
          <p>Fragrant basmati rice cooked with vegetables and special masala.</p>
        </div>

        <div class="card">
          <img src="dish6.jpg" alt="Dish 6">
          <h4>Hyderabadi Biryani (Chicken)</h4>
          <p>Layered chicken biryani slow-cooked with saffron and spices.</p>
        </div>

        <div class="card">
          <img src="dish7.jpg" alt="Dish 7">
          <h4>Rasam & Rice</h4>
          <p>Comforting tangy rasam served with steamed rice.</p>
        </div>

        <div class="card">
          <img src="dish8.jpg" alt="Dish 8">
          <h4>Idli Sambhar</h4>
          <p>Soft idlis with flavorful sambar and chutney.</p>
        </div>

        <div class="card">
          <img src="dish9.jpg" alt="Dish 9">
          <h4>Gobi 65</h4>
          <p>Spicy deep-fried cauliflower with curry leaf tempering.</p>
        </div>

        <div class="card">
          <img src="dish10.jpg" alt="Dish 10">
          <h4>Egg Curry</h4>
          <p>Boiled eggs in a spicy onion-tomato gravy.</p>
        </div>

        <div class="card">
          <img src="dish11.jpg" alt="Dish 11">
          <h4>Curd Rice</h4>
          <p>Comforting curd rice with seasoning of mustard seeds and curry leaf.</p>
        </div>

        <div class="card">
          <img src="dish12.jpg" alt="Dish 12">
          <h4>Filter Coffee</h4>
          <p>Traditional South Indian filter coffee to finish your meal.</p>
        </div>
      </div>
    </section>

    <footer class="footer">
      <div class="left">Color Scheme: Charcoal / Coral / Cream</div>
      <div class="right">Designed by Jothimani P</div>
    </footer>
  </div>
</body>
</html>


```
```

## OUTPUT:

![alt text](<Screenshot (37).png>)
![alt text](<Screenshot (38).png>)
![alt text](<Screenshot (39).png>)
![alt text](<Screenshot (40).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
