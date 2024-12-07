# Ex04 Places Around Me
# Date:20/11/24
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
~~~
<!DOCTYPE html>
<html>

<head>
    <title>IMAGEMAP</title>
    <link rel="icon" href="image.png"> 
</head>

<body style="background-color: black;">
    <h1>
        <marquee style="color: antiquewhite;">IMAGE MAP</marquee>
    </h1>
    <center>
        <img src="image.png" usemap="#image-map">
    </center>

    <map name="image-map"> 
        <area shape="rect" alt="Nandambakkam" title="Nandambakkam" href="http://127.0.0.1:5502/nandhanbakkam.html" coords="32,81,179,141" target="_blank">
        <area shape="rect" alt="Chrompet" title="Chrompet" href="http://127.0.0.1:5502/chrompet.html" coords="974,435,1125,486" target="_blank">
        <area shape="rect" alt="Tanishq" title="Tanishq" href="http://127.0.0.1:5502/tanishq.html" coords="920,717,1058,783" target="_blank">
        <area shape="rect" alt="GRT" title="GRT" href="http://127.0.0.1:5502/GRT.html" coords="798,612,843,640" target="_blank">
        <area shape="rect" alt="GN Tyres" title="GN Tyres" href="http://127.0.0.1:5502/GNtyres.html" coords="835,573,884,607" target="_blank">
        <area shape="rect" alt="VELS TECH" title="VELS TECH" href="http://127.0.0.1:5502/velstech.html" coords="1063,345,1206,420" target="_blank">
    
    </map>

    <h2 style="color: antiquewhite;">
        <marquee behavior="" direction="">IMAGE MAPPING IN HTML (K.DILLI BABU) 24900561 CSE(IOT) SAVEETHA ENGINEERING COLLEGE</marquee>
    </h2>
</body>

</html>
~~~
##gn tyres
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GN Tyres</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #2c3e50;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            color: #2c3e50;
            text-decoration: none;
        }
        main {
            padding: 20px;
        }
        section {
            margin-bottom: 20px;
            background: white;
            padding: 15px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            padding: 10px;
            background: #2c3e50;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to GN Tyres</h1>
</header>

<nav>
    <a href="#about">About Us</a>
    <a href="#products">Our Products</a>
    <a href="#services">Our Services</a>
    <a href="#contact">Contact Us</a>
</nav>

<main>
    <section id="about">
        <img src="gn.jpg" alt="gn">
        <h2>About GN Tyres</h2>
        <p>GN Tyres is a leading provider of high-quality tyres for all types of vehicles. With years of experience in the industry, we are committed to delivering the best products and services to our customers.</p>
    </section>

    <section id="products">
        <h2>Our Products</h2>
        <ul>
            <li>Passenger Car Tyres</li>
            <li>SUV and 4x4 Tyres</li>
            <li>Truck and Bus Tyres</li>
            <li>Motorcycle Tyres</li>
            <li>Specialty Tyres</li>
        </ul>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <ul>
            <li>Tyre Installation</li>
            <li>Tyre Rotation and Balancing</li>
            <li>Wheel Alignment</li>
            <li>Tyre Repair Services</li>
            <li>24/7 Emergency Assistance</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>If you have any questions or need assistance, feel free to reach out!</p>
        <p>Email: support@gntyres.com</p>
        <p>Phone: +1 (234) 567-8901</p>
        <p>Location: 123 Tyre Street, City, State, ZIP</p>
    </section>
</main>

<footer>
    <p>&copy; 2024 GN Tyres. All Rights Reserved.</p>
</footer>

</body>
</html>
~~~
##vels tech
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vels Tech</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #007bff;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            color: #007bff;
            text-decoration: none;
        }
        main {
            padding: 20px;
        }
        section {
            margin-bottom: 20px;
            background: white;
            padding: 15px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            padding: 10px;
            background: #007bff;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to Vels Tech</h1>
</header>

<nav>
    <a href="#about">About Us</a>
    <a href="#services">Our Services</a>
    <a href="#products">Our Products</a>
    <a href="#contact">Contact Us</a>
</nav>


<main>
    <section id="about">
        <img src="vels.jpg" alt="velstech">
        <h2>About Vels Tech</h2>
        <p>Vels Tech is a leading technology solutions provider dedicated to delivering innovative and effective solutions for businesses and individuals. Our mission is to empower our clients with the latest technology to enhance their productivity and success.</p>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <ul>
            <li>Software Development</li>
            <li>Web Development</li>
            <li>Mobile App Development</li>
            <li>IT Consulting</li>
            <li>Cloud Solutions</li>
        </ul>
    </section>

    <section id="products">
        <h2>Our Products</h2>
        <ul>
            <li>Project Management Software</li>
            <li>Customer Relationship Management (CRM) Tools</li>
            <li>E-commerce Solutions</li>
            <li>Mobile Applications</li>
            <li>Data Analytics Tools</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>If you have any questions or need assistance, feel free to reach out!</p>
        <p>Email: support@velstech.com</p>
        <p>Phone: +1 (234) 567-8901</p>
        <p>Location: 456 Tech Avenue, City, State, ZIP</p>
    </section>
</main>

<footer>
    <p>&copy; 2024 Vels Tech. All Rights Reserved.</p>
</footer>

</body>
</html>
~~~
##nandhanbakkam
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nandhampakkam</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #35424a;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            color: #35424a;
            text-decoration: none;
        }
        main {
            padding: 20px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background: #35424a;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body


<header>
    <h1>Welcome to Nandhampakkam</h1>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#attractions">Attractions</a>
    <a href="#contact">Contact</a>
</nav>

<main></main>
    <section id="about">
        <img src="nandambakkam.jpg" alt="xyz">
        <h2>About Nandhampakkam</h2>
        <p>Nandhampakkam is a beautiful locality known for its serene environment and vibrant culture. It is a great place to explore local traditions and enjoy the natural beauty.</p>
    </section>

    <section id="attractions">
        <h2>Attractions</h2>
        <ul>
            <li>Local Temples</li>
            <li>Parks and Recreation Areas</li>
            <li>Cultural Festivals</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>If you have any questions or need more information, feel free to reach out!</p>
        <p>Email: info@nandhampakkam.com</p>
    </section>
</main>

<footer>
    <p>&copy; 2023 Nandhampakkam. All Rights Reserved.</p>
</footer>

</body>
</html>
~~~
##chrompet
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chrompet, Chennai</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #007bff;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            color: #007bff;
            text-decoration: none;
        }
        main {
            padding: 20px;
        }
        section {
            margin-bottom: 20px;
            background: white;
            padding: 15px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            padding: 10px;
            background: #007bff;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to Chrompet, Chennai</h1>
</header>

<nav>
    <a href="#about">About Chrompet</a>
    <a href="#attractions">Local Attractions</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact Us</a>
</nav>

<main>
    <section id="about">
        <img src="chrompet.jpg" alt="chrompet">
        <h2>About Chrompet</h2>
        <p>Chrompet is a vibrant locality in Chennai, known for its residential areas, educational institutions, and proximity to the Chennai International Airport. It is a well-connected area that offers a blend of urban living and community spirit.</p>
    </section>

    <section id="attractions">
        <h2>Local Attractions</h2>
        <ul>
            <li>Chrompet Lake</li>
            <li>Shri Siva Vishnu Temple</li>
            <li>Local Parks and Playgrounds</li>
            <li>Shopping Centers</li>
            <li>Nearby IT Parks</li>
        </ul>
    </section>

    <section id="services">
        <h2>Services Available</h2>
        <ul>
            <li>Grocery Stores</li>
            <li>Healthcare Facilities</li>
            <li>Educational Institutions</li>
            <li>Transportation Services</li>
            <li>Community Events</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>If you have any questions or need more information, feel free to reach out!</p>
        <p>Email: info@chrompet.com</p>
        <p>Phone: +91 98765 43210</p>
        <p>Location: Chrompet, Chennai, Tamil Nadu, India</p>
    </section>
</main>

<footer>
    <p>&copy; 2024 Chrompet Community. All Rights Reserved.</p>
</footer>

</body>
</html>
~~~
##tanishq
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tanishq - The Trusted Name in Jewelry</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #c0a16b;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            color: #c0a16b;
            text-decoration: none;
        }
        main {
            padding: 20px;
        }
        section {
            margin-bottom: 20px;
            background: white;
            padding: 15px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            padding: 10px;
            background: #c0a16b;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to Tanishq</h1>
    <p>Your Trusted Name in Jewelry</p>
</header>

<nav>
    <a href="#about">About Tanishq</a>
    <a href="#products">Our Products</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact Us</a>
</nav>

<main>
    <section id="about">
        <h2>About Tanishq</h2>
        <p>Tanishq is a renowned jewelry brand in India, known for its exquisite designs and high-quality craftsmanship. With a wide range of gold, diamond, and platinum jewelry, Tanishq caters to every occasion and celebration.</p>
    </section>
<img src="tanisqh.png" alt="tanishq">
    <section id="products">
        <h2>Our Products</h2>
        <ul>
            <li>Gold Jewelry</li>
            <li>Diamond Jewelry</li>
            <li>Platinum Jewelry</li>
            <li>Bridal Collections</li>
            <li>Fashion Jewelry</li>
        </ul>
    </section>

    <section id="services">
        <h2>Services Available</h2>
        <ul>
            <li>Custom Jewelry Design</li>
            <li>Jewelry Repair Services</li>
            <li>Gold Exchange Program</li>
            <li>Gift Wrapping Services</li>
            <li>Online Shopping</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>If you have any questions or need assistance, feel free to reach out!</p>
        <p>Email: support@tanishq.com</p>
        <p>Phone: +91 98765 43210</p>
        <p>Location: Tanishq Showroom, Chennai, Tamil Nadu, India</p>
    </section>
</main>

<footer>
    <p>&copy; 2024 Tanishq. All Rights Reserved.</p>
</footer>

</body>
</html>
~~~

# OUTPUT
![Screenshot 2024-12-07 195545](https://github.com/user-attachments/assets/4909632a-e7ad-4272-8d86-4057a4272827)
![Screenshot 2024-12-07 195807](https://github.com/user-attachments/assets/4755f5c0-c362-4318-b0fb-e8d0ee1e7e80)
![Screenshot 2024-12-07 195928](https://github.com/user-attachments/assets/dcacb5c4-829d-4e45-8f5a-b7149ba54808)
![Screenshot 2024-12-07 200020](https://github.com/user-attachments/assets/ae00ea40-5fe7-47e2-957e-f971b4d6df36)
![Screenshot 2024-12-07 200119](https://github.com/user-attachments/assets/64910509-3fa0-4173-8044-bb598a035a1f)
![Screenshot 2024-12-07 200155](https://github.com/user-attachments/assets/188fc529-e775-4b01-a566-9b1897da548f)
![Screenshot 2024-12-07 200242](https://github.com/user-attachments/assets/f4921ff9-f21d-49d3-bf09-d2ef2bf3fd23)

# RESULT
The program for implementing image maps using HTML is executed successfully.
