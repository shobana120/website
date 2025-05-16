# Ex.07 Restaurant Website
# Date:
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Our Restaurant</title>
  <link rel="stylesheet" href="c:\Users\admin\Desktop\WEB\New\style css.css">
</head>
<body>
  <header>
    <h1>BISTRO BITES RESTAURANT</h1>
    <nav>
      <a href="file:///C:/Users/admin/Desktop/WEB/New/menu.html">Menu</a>
      <a href="file:///C:/Users/admin/Desktop/WEB/New/team.html">Team</a>
      <a href="file:///C:/Users/admin/Desktop/WEB/New/contact.html">Contact Us</a>
    </nav>
  </header>

  <section id="logo-details">
    <div class="logo-container">
      <img src="c:\Users\admin\Downloads\Bistro Bytes.png">
    </div>
    <div class="restaurant-details">
      <h2>Welcome to BISTRO BITES RESTAURANT</h2>
      <p>
        Located in the heart of Chennai, BISTRO BITES Restaurant offers a memorable dining experience with a focus on high-quality food and exceptional service. Our mission is to provide a wide variety of delicious dishes made from fresh, locally sourced ingredients in a warm and inviting atmosphere. Whether it's a casual meal or a special occasion, we have something for everyone!
      </p>
      <p>
        Come visit us and enjoy delightful meals, friendly service, and an atmosphere that feels like home.
      </p>
    </div>
  </section>
  
  <main>
    <!-- About Us Section -->
    <section id="about">
        <h2>About Us</h2>
        <img src="c:\Users\admin\Downloads\pexels-photo-1123262.webp" alt="About Us Image" class="about-image">
        <p>
          Welcome to <strong> Restaurant</strong>, where passion for food and love for service come together to create a truly unforgettable dining experience. Founded by Visves, an 18-year-old food enthusiast, our restaurant strives to offer both comfort and culinary delight for every guest who walks through our doors.
        </p>
        <p>
          At  Restaurant, we believe that food is more than just a meal – it's an experience. Our menu is carefully crafted to offer a blend of traditional favorites and innovative dishes, all made with the finest ingredients. Whether you're in the mood for a delicious pizza, a comforting bowl of pasta, or something new and exciting, our team is here to delight your taste buds.
        </p>
        <p>
          We are committed to providing not only mouthwatering dishes but also exceptional service in a warm and welcoming atmosphere. From the moment you enter, you'll be greeted by our friendly staff who are dedicated to making your dining experience perfect.
        </p>
        <p>
          Located in the heart of Chennai, we take pride in our local roots and the strong relationships we’ve built with local farmers and suppliers. We strive to use fresh, locally sourced ingredients, ensuring that every dish we serve is of the highest quality.
        </p>
        <p>
          Our mission is simple – to create a space where you can come together with family, friends, and loved ones to share delicious food and make lasting memories. Whether you're here for a special occasion, a casual meal, or simply to enjoy a drink, Visves Restaurant is your go-to destination for great food and hospitality.
        </p>
        <p>
          Thank you for choosing us! We look forward to serving you and ensuring that every meal is one you'll remember.
        </p>
      </section>
      

    <!-- Menu Section -->
    <section id="menu">
        <h2>Our Menu</h2>
        
        
        <div class="menu-list">
          <div class="menu-item">
            <img src="c:\Users\admin\Downloads\download.jpeg" alt="Pizza" class="menu-item-image">
            <p>Pizza</p>
          </div>
          <div class="menu-item">
            <img src="c:\Users\admin\Downloads\download (1).jpeg" alt="Burger" class="menu-item-image">
            <p>Burger</p>
          </div>
          <div class="menu-item">
            <img src="c:\Users\admin\Downloads\download (2).jpeg" alt="Pasta" class="menu-item-image">
            <p>Pasta</p>
          </div>
          <div class="menu-item">
            <img src="c:\Users\admin\Downloads\download (3).jpeg" alt="Salad" class="menu-item-image">
            <p>Salad</p>
          </div>
          <div class="menu-item">
            <img src="c:\Users\admin\Downloads\download (4).jpeg" alt="Sushi" class="menu-item-image">
            <p>Sushi</p>
          </div>
          <div class="menu-item">
            <img src="c:\Users\admin\Downloads\download (5).jpeg" alt="Steak" class="menu-item-image">
            <p>Steak</p>
          </div>
          <div class="menu-item">
            <img src="c:\Users\admin\Downloads\download (6).jpeg" alt="Fries" class="menu-item-image">
            <p>Fries</p>
          </div>
          <div class="menu-item">
            <img src="c:\Users\admin\Downloads\download (7).jpeg" alt="Ice Cream" class="menu-item-image">
            <p>Ice Cream</p>
          </div>
        </div>
      </section>

    <!-- Team Section -->
    <section id="team">
      <h2>Our Team</h2>
      <div class="team">
        <div class="member">
          <img src="c:\Users\admin\Downloads\download (8).jpeg" alt="Team Member 2">
          <p>Jane Smith - Chef</p>
        </div>
        <div class="member">
          <img src="c:\Users\admin\Downloads\download (10).jpeg" alt="Team Member 3">
          
        </div>
        <div class="member">
            <img src="c:\Users\admin\Downloads\download (9).jpeg" alt="Team Member 2">
            <p>Steve Smith - Chef</p>
          </div>
          <div class="member">
            <img src="c:\Users\admin\Downloads\download (11).jpeg" alt="Team Member 2">
            
          </div>
      </div>
    </section>

    <!-- Contact Us Section -->
    <section id="contact">
      <h2>Contact Us</h2>
      <p>Address: 123 Food Street, Chennai, India</p>
      <p>Phone: +91 7558188817</p>
      <p>Email: revengeythmm123@gmail.com</p>
    </section>
  </main>

  
</body>
</html>
menu.html 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Menu</title>
  <link rel="stylesheet" href="c:\Users\admin\Desktop\WEB\New\style css.css">
</head>
<body>
  <header>
    <h1>Our Menu</h1>
    <nav>
        <a href="file:///C:/Users/admin/Desktop/WEB/New/menu.html">Menu</a>
        <a href="file:///C:/Users/admin/Desktop/WEB/New/team.html">Team</a>
        <a href="file:///C:/Users/admin/Desktop/WEB/New/contact.html">Contact Us</a>
    </nav>
  </header>
  <main>
    <h2>Delicious Dishes</h2>
    <div class="menu-grid">
      <div class="menu-item" onclick="showDetails('Pizza', 'images/pizza.jpg')">
        <img src="c:\Users\admin\Downloads\download.jpeg" alt="Pizza">
        <p>Pizza</p>
      </div>
      <div class="menu-item" onclick="showDetails('Burger', 'images/burger.jpg')">
        <img src="c:\Users\admin\Downloads\download (1).jpeg" alt="Burger">
        <p>Burger</p>
      </div>
      <div class="menu-item" onclick="showDetails('Pasta', 'images/pasta.jpg')">
        <img src="c:\Users\admin\Downloads\download (2).jpeg" alt="Pasta">
        <p>Pasta</p>
      </div>
      <div class="menu-item" onclick="showDetails('Salad', 'images/salad.jpg')">
        <img src="c:\Users\admin\Downloads\download (3).jpeg" alt="Salad">
        <p>Salad</p>
      </div>
      <div class="menu-item" onclick="showDetails('Salad', 'images/salad.jpg')">
        <img src="c:\Users\admin\Downloads\download (4).jpeg" alt="Sushi">
        <p>Sushi</p>
      </div>
      <div class="menu-item" onclick="showDetails('Salad', 'images/salad.jpg')">
        <img src="c:\Users\admin\Downloads\download (5).jpeg" alt="Steak">
        <p>Steak</p>
      </div>
      <div class="menu-item" onclick="showDetails('Salad', 'images/salad.jpg')">
        <img src="c:\Users\admin\Downloads\download (6).jpeg" alt="fries">
        <p>Fries</p>
        </div>
        <div class="menu-item" onclick="showDetails('Salad', 'images/salad.jpg')">
            <img src="c:\Users\admin\Downloads\download (7).jpeg" alt="Icecream">
            <p>Icecream</p>
          </div>
    </div>
    <div id="food-details" class="food-details">
      <!-- Food details will display dynamically here -->
    </div>
  </main>
    <script>
    function showDetails(name, imgSrc) {
      const details = document.getElementById('food-details');
      details.innerHTML = `
        <h3>${name}</h3>
        <img src="${imgSrc}" alt="${name}" style="width:300px; height:auto; margin-top:10px;">
      `;
    }
  </script>
</body>
</html>
contact
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us</title>
  <link rel="stylesheet" href="c:\Users\admin\Desktop\WEB\New\style css.css">
</head>
<body>
  <header>
    <h1>Contact Us</h1>
    <nav>
        <a href="file:///C:/Users/admin/Desktop/WEB/New/menu.html">Menu</a>
        <a href="file:///C:/Users/admin/Desktop/WEB/New/team.html">Team</a>
        <a href="file:///C:/Users/admin/Desktop/WEB/New/contact.html">Contact Us</a>
    </nav>
  </header>
  <main>
    <h2>Get in Touch</h2>
       <p>Address: 123 Food Street, Chennai, India</p>
    <p>Phone: +91 9876543210</p>
    <p>Email: contact@restaurant.com</p>
  </main>
</body>
</html>

<!-- admin.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About Me</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>About Me</h1>
    <nav>
      <a href="index.html">About Me</a>
      <a href="menu.html">Menu</a>
      <a href="admin.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>
  <main>
    <section class="about">
      <h2>About Me</h2>
      <img src="c:\Users\admin\Downloads\pexels-photo-1123262.webp" alt="About Us Image" class="about-image">
      <p>an 18-year-old food enthusiast with a passion for creating vibrant dining experiences. Our restaurant aims to provide delicious meals with excellent service in a welcoming atmosphere. Whether you're here for a quick snack or a fine dining experience, we've got you covered. Come and explore our menu!</p>
    </section>
  </main>
  
</body>
</html>

<html>
    <centre>
<!-- Team Section -->
 <centre>
<section id="team">
    <h2>Our Team</h2>
    <div class="team">
      <tr>
      <div class="member">
        <img src="c:\Users\admin\Downloads\download (8).jpeg"> 
       </div>
       <br>
      <div class="member">
        <img src="c:\Users\admin\Downloads\download (10).jpeg">
      </div>
      <br>
      <div class="member">
          <img src="c:\Users\admin\Downloads\download (9).jpeg">
        </div>
        <br>
        <div class="member">
          <img src="c:\Users\admin\Downloads\download (11).jpeg" >
        </div>
        <br>
      </tr>
    </div>
  </centre>
</centre>
  </section>
```

# OUTPUT:
![Screenshot 2025-05-16 225832](https://github.com/user-attachments/assets/1067abaa-2280-4e65-aac7-e6fc49ad7b3c)
![Screenshot 2025-05-16 225857](https://github.com/user-attachments/assets/5401fd57-f733-410b-a1d9-6e29ae3dd892)
![Screenshot 2025-05-16 225951](https://github.com/user-attachments/assets/452a12e2-6953-458d-88b4-375e1f6f9d74)
![Screenshot 2025-05-16 230014](https://github.com/user-attachments/assets/f2d0c32b-94ce-4e1a-bfd6-20cadc2cb091)
![Screenshot 2025-05-16 230055](https://github.com/user-attachments/assets/eedf72f4-c607-4519-9151-e209a4851595)
![Screenshot 2025-05-16 230115](https://github.com/user-attachments/assets/af7f710e-010a-48a7-bdff-0f215668336f)




# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
