# Ex.07 Restaurant Website
## Date:8.10.2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

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
1.Home page

index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>GreenLeaf Veg Restaurant</title>
    <link rel="stylesheet" href="home.css">
</head>
<body>
    <header>
        
        <nav>
            <a href="index.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="administration.html">Administration</a>
            <a href="contactus.html">Contact Us</a>
        </nav>
    </header>
    <main>
        <h1>Welcome to GreenLeaf Veg Restaurant</h1>
        <p>Enjoy the taste of fresh vegetarian delicacies in a comfortable and friendly atmosphere. Our chefs use only the finest ingredients to create dishes you'll love!</p>
    </main>
    <footer>
        <p>Designed by [Samritha G]</p>
    </footer>
</body>
</html>

home.css

body {
    background: #fffef4;
    color: #333333;
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}
header {
    background: #47a447;
    padding: 0;
    text-align: center;
}

nav {
    background: #ff9800;
    padding: 15px 0;
}
nav a {
    color: #fffef4;
    text-decoration: none;
    margin: 0 25px;
    font-size: 18px;
    font-weight: bold;
}
nav a:hover {
    color: #47a447;
}
main {
    padding: 40px 20px;
    text-align: center;
}
footer {
    background: #47a447;
    color: #fffef4;
    text-align: center;
    padding: 15px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}

2.Menu page

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Menu - GreenLeaf Veg Restaurant</title>
    <link rel="stylesheet" href="menu.css">
</head>
<body>
    <header>
        
        <nav>
            <a href="index.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="administration.html">Administration</a>
            <a href="contactus.html">Contact Us</a>
        </nav>
    </header>
    <main>
        <h1>Our Vegetarian Specialties</h1>
        <div class="menu-list">
            <div class="menu-item"><h3>Paneer Tikka</h3><p>Grilled cottage cheese with spices</p></div>
            <div class="menu-item"><h3>Veg Biryani</h3><p>Basmati rice with mixed vegetables</p></div>
            <div class="menu-item"><h3>Daal Makhani</h3><p>Rich lentil curry with cream</p></div>
            <div class="menu-item"><h3>Aloo Gobi</h3><p>Potato & cauliflower stir fry</p></div>
            <div class="menu-item"><h3>Chole Bhature</h3><p>Spicy chickpeas with fried bread</p></div>
            <div class="menu-item"><h3>Veg Manchurian</h3><p>Vegetable balls in tangy sauce</p></div>
            <div class="menu-item"><h3>Navratan Korma</h3><p>Mixed veggies in creamy gravy</p></div>
            <div class="menu-item"><h3>Hara Bhara Kabab</h3><p>Spinach and peas patties</p></div>
            <div class="menu-item"><h3>Methi Malai Matar</h3><p>Green peas & fenugreek in cream</p></div>
            <div class="menu-item"><h3>Stuffed Naan</h3><p>Indian bread with fillings</p></div>
            <div class="menu-item"><h3>Veg Soup</h3><p>Mixed veg soup starter</p></div>
            <div class="menu-item"><h3>Gulab Jamun</h3><p>Syrupy dessert balls</p></div>
        </div>
    </main>
    <footer>
        <p>Designed by [Samritha G]</p>
    </footer>
</body>
</html>

menu.css

body {
    background: #fffef4;
    color: #333333;
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}
header {
    background: #47a447;
}

nav {
    background: #ff9800;
    padding: 15px 0;
    text-align: center;
}
nav a {
    color: #fffef4;
    text-decoration: none;
    margin: 0 25px;
    font-size: 18px;
    font-weight: bold;
}
nav a:hover {
    color: #47a447;
}
main {
    padding: 30px;
    text-align: center;
}
.menu-list {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 18px;
    margin-top: 24px;
}
.menu-item {
    background: #e4ffe4;
    padding: 18px;
    border-radius: 11px;
    box-shadow: 0 4px 18px #aaa;
}
.menu-item img {
    width: 120px;
    height: 90px;
    object-fit: cover;
    border-radius: 10px;
}
.menu-item h3 {
    color: #47a447;
    margin: 14px 0 8px 0;
}
.menu-item p {
    color: #333;
    font-size: 16px;
}
footer {
    background: #47a447;
    color: #fffef4;
    text-align: center;
    padding: 15px 0;
    margin-top: 40px;
}

3.administration page

administration.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Administration - GreenLeaf Veg Restaurant</title>
    <link rel="stylesheet" href="admin.css">
</head>
<body>
    <header>
        
        <nav>
            <a href="index.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="administration.html">Administration</a>
            <a href="contactus.html">Contact Us</a>
        </nav>
    </header>
    <main>
        <h1>Meet Our Team</h1>
        <div class="admin-list">
            <div class="admin-member"><h3>Priya Mehta</h3><p>Manager</p></div>
            <div class="admin-member"><h3>Rajan Menon</h3><p>Head Chef</p></div>
            <div class="admin-member"><h3>Ananya Gupta</h3><p>Sous Chef</p></div>
            <div class="admin-member"><h3>Sunil Kumar</h3><p>Receptionist</p></div>
            <div class="admin-member"><h3>Sneha Sharma</h3><p>Host</p></div>
            <div class="admin-member"><h3>Amit Verma</h3><p>Waiter</p></div>
        </div>
    </main>
    <footer>
        <p>Designed by [Samritha G]</p>
    </footer>
</body>
</html>

admin.css

body {
    background: #fffef4;
    color: #333333;
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}
header {
    background: #47a447;
}

nav {
    background: #ff9800;
    padding: 15px 0;
    text-align: center;
}
nav a {
    color: #fffef4;
    text-decoration: none;
    margin: 0 25px;
    font-size: 18px;
    font-weight: bold;
}
nav a:hover {
    color: #47a447;
}
main {
    padding: 30px;
    text-align: center;
}
.admin-list {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 28px;
    margin-top: 24px;
}
.admin-member {
    background: #e4ffe4;
    padding: 18px;
    border-radius: 11px;
    width: 200px;
    box-shadow: 0 4px 18px #aaa;
    text-align: center;
}
.admin-member img {
    width: 100px;
    height: 100px;
    object-fit: cover;
    border-radius: 50%;
}
.admin-member h3 {
    color: #47a447;
    margin: 14px 0 8px 0;
}
.admin-member p {
    color: #ff9800;
    font-size: 16px;
    margin: 0;
}
footer {
    background: #47a447;
    color: #fffef4;
    text-align: center;
    padding: 15px 0;
    margin-top: 40px;
}

4.Contact page

contactus.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Contact Us - GreenLeaf Veg Restaurant</title>
    <link rel="stylesheet" href="contact.css">
</head>
<body>
    <header>
       
        <nav>
            <a href="index.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="administration.html">Administration</a>
            <a href="contactus.html">Contact Us</a>
        </nav>
    </header>
    <main>
        <h1>Contact Us</h1>
        <div class="contact-info">
            <p><strong>Address:</strong> 123 Green Street, Chennai,Tamil nadu</p>
            <p><strong>Phone:</strong> +91-9876543210</p>
            <p><strong>Email:</strong> info@greenleafveg.com</p>
        </div>
    </main>
    <footer>
        <p>Designed by [Samritha G]</p>
    </footer>
</body>
</html>

contact.css

body {
    background: #fffef4;
    color: #333333;
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}
header {
    background: #47a447;
}

nav {
    background: #ff9800;
    padding: 15px 0;
    text-align: center;
}
nav a {
    color: #fffef4;
    text-decoration: none;
    margin: 0 25px;
    font-size: 18px;
    font-weight: bold;
}
nav a:hover {
    color: #47a447;
}
main {
    padding: 30px;
    text-align: center;
}
.contact-info {
    background: #e4ffe4;
    border-radius: 8px;
    padding: 18px;
    display: inline-block;
    margin-top: 22px;
}
.contact-info p {
    color: #333333;
    font-size: 18px;
    margin: 14px 0;
}
footer {
    background: #47a447;
    color: #fffef4;
    text-align: center;
    padding: 15px 0;
    margin-top: 40px;
}
~~~

## OUTPUT:

![alt text](<home page.png>)
![alt text](<menu page.png>)
![alt text](<administration page.png>)
![alt text](<contact page.png>)




## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
