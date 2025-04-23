# Ex04 Places Around Me
<<<<<<< HEAD
## Date: 23/04/2025
=======
## Date: 23.04.2025
>>>>>>> 0ae9ef212923039bbf741116c85fd32383ab8b3a

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
<<<<<<< HEAD
``` 
map.html 
<html>
    <head>
        <title>Places in Thiruvananthapuram</title>
        <h1 align="center">Thiruvananthapuram</h1>
        <h1 align="center">Created by: AJITH A (212224230012)</h1>
    </head>
    <body bgcolor="silver"> 
        <img src="tvc.png" usemap="#image-map">
        <map name="image-map">
            <area target="" alt="Padmanabha Swamy Temple" title="Padmanabha Swamy Temple" href="swa.html" coords="1003,491,1198,535" shape="rect">
            <area target="" alt="Thiruvananathapuram International Airport" title="Thiruvananathapuram International Airport" href="air.html" coords="646,560,853,617" shape="rect">
            <area target="" alt="Thiruvananthapuram Zoological Park" title="Thiruvananthapuram Zoological Park" href="zoo.html" coords="1153,81,1405,151" shape="rect">
            <area target="" alt="Veli Beach" title="Veli Beach" href="veli.html" coords="29,116,258,181" shape="rect">
            <area target="" alt="Attukal Bhagavathy Temple" title="Attukal Bhagavathy Temple" href="bha.html" coords="1188,686,37" shape="circle">
        </map>
    </body>
</html>

air.html
<html>
    <head>
        <title>Airport</title>
    </head>
    <body bgcolor="LightSkyBlue">
        <h1 align="center">Thiruvananthapuram International Airport</h1>
        <h2 align="center">Eanchakkal,Thiruvananthapuram</h2>
        <hr size="3" color="LightSteelBlue">
        <br><br>
        <p><h3>Thiruvananthapuram International Airport (IATA: TRV), is an international airport that serves Thiruvananthapuram, the capital city of Kerala, India. Established in 1932, it is the first airport in the state of Kerala and the fifth international airport of India, officially declared in 1991.It is the operating base of Air India, Air India Express, IndiGo and SpiceJet.</h3></p>
    </body>
</html>

bha.html
<html>
    <head>
        <title>Attukal</title>
    </head>
    <body bgcolor="Crimson">
        <h1 align="center">Attukal Bhagavathy Temple</h1>
        <h2 align="center">Attukal,Manacaud,Thiruvananthapuram</h2>
        <hr size="3" color="Darkgoldenrod">
        <br><br>
        <p><h3>The Attukal Bhagavathy Temple is a Hindu religious shrine at Attukal in Kerala, India. Goddess Bhadrakali (Kannaki), mounted over 'vethala', is the main deity in this temple.The Goddess Kannaki (Bhadrakali) is the main deity in this temple. Attukal Pongala is the main. Attukal Pongala Mahotsavam is a 10 days festival which falls on February-March every year .</h3></p>
    </body>
</html>

swa.html
<head>
    <title>Padmanabhaswamy</title>
</head>
<body bgcolor="Mistyrose">
    <h1 align="center">Anantha Padmanabhaswamy Temple</h1>
    <h2 align="center">East Fort,Thiruvananthapuram</h2>
    <hr size="3" color="MediumVioletRed">
    <br><br>
    <p><h3>The Padmanabhaswamy Temple is a Hindu temple, dedicated to Vishnu, in Thiruvananthapuram, the capital of the state of Kerala, India. It is one of the 108 Divya Desams, the sacred abodes of Vishnu in the Sri Vaishnava tradition. It is widely considered as the world's richest Hindu temple.The temple is built in an intricate fusion of the Kerala style and the Dravidian style of architecture, featuring high walls, and a 16th-century gopuram.</h3></p>
</body>
</html>

veli.html
<html>
    <head>
        <title>Veli</title>
    </head>
    <body bgcolor="Navajowhite">
        <h1 align="center">Veli Lake Tourist Village</h1>
        <h2 align="center">Veli,Thiruvananthapuram</h2>
        <hr size="5" color="Powderblue">
        <br><br>
        <p><h3>The Veli Tourist Village which lies where the Veli Lake meets the Arabian Sea provides for unique boating and picnicking opportunities. Visitors can hire pedal boats or paddleboats as per their convenience. One can also roam the gardens and have a nice picnic or choose to employ the boats for the entire duration of the trip.</h3></p>
    </body>
</html>

zoo.html
<html>
    <head>
        <title>Zoological Park</title>
    </head>
    <body bgcolor="aquamarine">
        <h1 align="center">Thiruvananathapuram Zoological Park and Napier Museum</h1>
        <h2 align="center">Palayam,Thiruvananthapuram</h2>
        <hr size="3" color="cornflowerblue">
        <br><br>
        <p><h3>Thiruvananthapuram Zoo is one of the oldest zoos in India. It occupies 55 acres (22 ha) of woodland, lakes, and lawns.It is home to 82 species from around the world.Similarly the Museum and Botanical Gardens are also one of the oldest of their kind in the country. Swathi Thirunal Rama Varma (1816-1846), the ruler of Travancore during 1830-1846, was the visionary behind the establishment of the Thiruvananthapuram Museum and Zoo.</h3></p>
    </body>
</html>
```
=======
'''
map.html
<html>
<head>
    <title>My City</title>
</head>
<body>

    <h1 align="center">
        <font color="red"><b>Vaniyambadi</b></font>
    </h1>
    <h3 align="center">
      <font color="blue"><b>Tharrun D (24900893)</b></font>
    </h3>
    <center>
        <img src="map.png" usemap="#MyCity">
        <map name="MyCity"> 
            <area shape="rect" coords="579,388,617,418" title="My House" href="house.html">
            <area shape="rect" coords="839,275,881,315" title="M S Hall" href="hall.html">
            <area shape="rect" coords="277,150,316,185" title="Ahmedia Hotel" href="hotel.html">
            <area shape="rect" coords="77,324,120,358" title="Shivan Temple" href="temple.html">
            <area shape="rect" coords="965,394,1011,434" title="High School" href="school.html">
        </map>
    </center>
</body>
</html>

hall.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My House</title>
    <style>
        body {
            background-color: lightblue; /* Background color for the page */
            font-family: Arial, sans-serif; /* Sets the font style */
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #4CAF50; /* Green header background */
            color: white;
            padding: 20px;
            text-align: center;
        }
        .content {
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>M S Hall</h1>
    </header>
    <div class="content">
        <p>A function hall is a versatile space designed to host various types of events and gatherings. It can accommodate personal, social, or corporate functions.The M.S. Hall may host various events such as weddings, conferences, community gatherings, or cultural celebrations. Its design and amenities are tailored to ensure a smooth and memorable experience for attendees. </p>
    </div>
</body>
</html>

hotel.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My House</title>
    <style>
        body {
            background-color: lightblue; /* Background color for the page */
            font-family: Arial, sans-serif; /* Sets the font style */
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #4CAF50; /* Green header background */
            color: white;
            padding: 20px;
            text-align: center;
        }
        .content {
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Ahmedia Hotel </h1>
    </header>
    <div class="content">
        <p>Ahmedia Hotel offers a blend of modern comfort and traditional charm, making it an ideal choice for travelers. Conveniently located, it provides exceptional hospitality, spacious accommodations, and world-class amenities. Whether for leisure or business, the hotel ensures a memorable stay.</p>
    </div>
</body>
</html>

house.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My House</title>
    <style>
        body {
            background-color: lightblue; /* Background color for the page */
            font-family: Arial, sans-serif; /* Sets the font style */
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #4CAF50; /* Green header background */
            color: white;
            padding: 20px;
            text-align: center;
        }
        .content {
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My House</h1>
    </header>
    <div class="content">
        <p>My house is a cozy and comfortable place where I live with my family. It has a beautiful garden in the front, a spacious living room, and a warm kitchen that fills the air with delightful aromas.</p>
        <p>The bedrooms are painted in soft, calming colors, and the walls are adorned with family photographs and artwork. My favorite spot is the balcony, where I enjoy watching sunsets and sipping tea.</p>
    </div>
</body>
</html>

school.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My House</title>
    <style>
        body {
            background-color: lightblue; /* Background color for the page */
            font-family: Arial, sans-serif; /* Sets the font style */
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #4CAF50; /* Green header background */
            color: white;
            padding: 20px;
            text-align: center;
        }
        .content {
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>High School</h1>
    </header>
    <div class="content">
        <p><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My House</title>
    <style>
        body {
            background-color: lightblue; /* Background color for the page */
            font-family: Arial, sans-serif; /* Sets the font style */
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #4CAF50; /* Green header background */
            color: white;
            padding: 20px;
            text-align: center;
        }
        .content {
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>High School</h1>
    </header>
    <div class="content">
        <p>High school is a transformative journey filled with growth and discovery. It's where friendships are forged, dreams take shape, and challenges build resilience. Each day brings new lessons, both in and out of the classroom. These years leave lasting memories and pave the way for a bright future.</p>
    </div>
</body>
</html>
    </div>
</body>
</html>

temple.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My House</title>
    <style>
        body {
            background-color: lightblue; /* Background color for the page */
            font-family: Arial, sans-serif; /* Sets the font style */
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #4CAF50; /* Green header background */
            color: white;
            padding: 20px;
            text-align: center;
        }
        .content {
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Shivan Temple</h1>
    </header>
    <div class="content">
        <p>Shivan Temple is a sacred place dedicated to Lord Shiva, known for its spiritual significance and architectural beauty. Devotees gather to offer prayers and experience peace in the serene atmosphere. The temple often features intricate carvings and rituals steeped in tradition, symbolizing devotion and divine energy.</p>
    </div>
</body>
</html>
'''
>>>>>>> 0ae9ef212923039bbf741116c85fd32383ab8b3a

## OUTPUT
![Screenshot (243)](https://github.com/user-attachments/assets/6c556caf-da0f-4a96-9ea5-b1884430715d)
![Screenshot (244)](https://github.com/user-attachments/assets/4ec455e6-cb35-465c-b190-6cff980c8706)
![Screenshot (245)](https://github.com/user-attachments/assets/a5bda4d6-8b8f-4e8f-b2de-95369305de76)
![Screenshot (246)](https://github.com/user-attachments/assets/ab88f0f1-6279-4123-9374-d1fb4a6ce3ae)
![Screenshot (247)](https://github.com/user-attachments/assets/2b1cb880-76cc-438e-a384-73641af1423f)
![Screenshot (248)](https://github.com/user-attachments/assets/57fc428e-d0c3-4204-a294-4c188e38374f)



![alt text](<Screenshot (251).png>)

![alt text](<Screenshot (252).png>)

![alt text](<Screenshot (253).png>)

![alt text](<Screenshot (255).png>) 

![alt text](<Screenshot (256).png>)

![alt text](<Screenshot (257).png>)





## RESULT
The program for implementing image maps using HTML is executed successfully.
