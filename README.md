# Ex04 Places Around Me
## Date: 28/09/2025

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
```
map.html
<html>
    <head>
        <title>My City</title>
        <link rel="stylesheet"href="style.css">
    </head>
<body bgcolor="cyan">
    <h1 align="center">
        <font color="brown">TIRUNELVELI - Sandya S - 25017264</font>
    </h1>
    <center>
        <img src="Screenshot 2025-09-28 201227.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Nellaiyappar" title="Nellaiyappar" href="nellaiyappar.html" coords="300,686,69,746" shape="rect">
    <area target="" alt="Koothartemple" title="Koothartemple" href="koothartemple.html" coords="660,504,128" shape="circle">
    <area target="" alt="Sasthakovil" title="Sasthakovil" href="sasthakovil.html" coords="760,337,800,291,1005,289,1008,385,800,385" shape="poly">
    <area target="" alt="Ammantemple" title="Ammantemple" href="ammantemple.html" coords="809,82,1022,146" shape="rect">
    <area target="" alt="Church" title="Church" href="church.html" coords="336,28,542,86" shape="rect">
</map>
     </center>
</body>
</html>

church.html
<html>
    <head>
        <title>
            Church
        </title>
    </head>
    <body bgcolor="lavender">
        <h1 align="center">
            <font color="mintgreen">TIRUNELVELI</font>
        </h1>
        <h2 align="center">
            <font color="deepviolet">ST ANTONY CHURCH</font>
        </h2>
        <p align="center">
            St. Antony's Church in Alavanthankulam, located approximately 15 km from Tirunelveli, Tamil Nadu, is a Roman Catholic parish under the Palayamkottai Diocese. Established on February 15, 1954, it serves the local community with regular mass services and spiritual guidance. The church is situated in a rural area, providing a peaceful environment for worship and reflection.
        </p>
    </body>
</html>

ammantemple.html
<html>
    <head>
        <title>
            Ammantemple
        </title>
    </head>
    <body bgcolor="green">
        <h1 align="center">
            <font color="blue">TIRUNELVELI</font>
        </h1>
        <h2 align="center">
            <font color="orange">SHRI ANGALESHWARI AMMAN TEMPLE</font>
        </h2>
        <p align="center">
            The Shri Angalaeswari Amman Temple in Naraikinaru, Tamil Nadu, is a revered Hindu shrine dedicated to Angalaeswari Amman, an incarnation of Goddess Parvati. Known for its spiritual significance, the temple attracts devotees seeking blessings for prosperity and well-being. The serene ambiance enhances the devotional experience.
        </p>
    </body>
</html>

sasthakovil.html
<html>
    <head>
        <title>
            Sasthakovil
        </title>
    </head>
    <body bgcolor="brown">
        <h1 align="center">
            <font color="cyan">TIRUNELVELI</font>
        </h1>
        <h2 align="center"> 
            <font color="blue">ARULMIGU SRI POOLUDAIYAR SASTHA KOVIL</font>
        </h2>
        <p align="center">
           Arulmigu Sri Pooludaiyar Sastha Kovil in Marukalthalai near Seevalaperi, Tirunelveli, is a Hindu temple dedicated to Sastha (Pooludaiyar), worshipped with Purna and Pushkala forms. It has many parivara moorthigal (auxiliary deities) such as Sangili Boothadar, Thalavai Madan, Malaiyazhagu Amman and others. Devotees believe that the main idol came into existence during a journey through forests and hills by seven men from Maniyachi, who felt divine protection from Sastha after observing miraculous signs. 
        </p>
    </body>
</html>

koothartemple.html
<html>
    <head>
        <title>
            Koothartemple
        </title>
    </head>
    <body bgcolor="yellow">
        <h1 align="center">
            <font color="green">TIRUNELVELI</font>
        </h1>
        <h2 align="center">
            <font color="blue">SRI SEPPARAI AZHAGIYA KOOTHAR TEMPLE</font>
        </h2>
        <p align="center">
            Arulmigu Sepparai Azhagiya Koothar Temple, in Rajavallipuram near Tirunelveli, is dedicated to Lord Natarajar (Azhagiya Koothar) and Goddess Kanthimathi. Situated close to the Thamirabarani river north bank, its vimana, sanctum, and tree (vilvam) and sacred water-body (Pushabadhan) hold ritual significance. Annual festivals include Aani Therottam and Margazhi Thiruvathira.
        </p>
    </body>
</html>

nellaiyappar.html
<html>
    <head>
        <title>
            Nellaiyappar
        </title>
    </head>
    <body bgcolor="orange">
        <h1 align="center">
            <font color="yellow">TIRUNELVELI</font>
        </h1>
        <h2 align="center">
            <font color="red">ARULMIGU NELLAIYAPPAR TEMPLE</font>
        </h2>
        <p align="center">
            Arulmigu Nellaiyappar Temple in Tirunelveli is a majestic Shaivite shrine, where Lord Shiva (as Nellaiappar) and his consort Kanthimathi Amman are worshipped. Its complex spans about 14.5 acres with multiple shrines, musical pillars and ornate mandapams. The temple is famous for grand festivals like the Aani Brahmotsavam, vibrant rituals and its presence in ancient Tamil literary works.
        </p>
    </body>
</html>

```


## OUTPUT
![alt text](<Screenshot (24).png>)
![alt text](<Screenshot (25).png>)
![alt text](<Screenshot (26).png>)
![alt text](<Screenshot (27).png>)
![alt text](<Screenshot (28).png>)
![alt text](<Screenshot (29).png>)



## RESULT
The program for implementing image maps using HTML is executed successfully.
