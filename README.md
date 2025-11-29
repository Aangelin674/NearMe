# Ex03 Places Around Me
## Date: 29.11.2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
```
map.html
<html>
    <head>
        <title>map</title>
    </head>
    <body bgcolor="white">
        <h1 align="center">TENKASI</h1>
        <h3 align="center">ANGELIN GRACY.R(25007261)</h3>
     <img src="Screenshot 2025-11-28 164604.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="yasuragi botique resort" title="yasuragi botique resort" href="yasuragi.html" coords="117,292,521,464" shape="rect">
    <area target="" alt="kings palace" title="kings palace" href="kings.html" coords="1584,106,123" shape="circle">
    <area target="" alt="hotel tamilnadu" title="hotel tamilnadu" href="hotel.html" coords="1117,522,1369,619" shape="rect">
    <area target="" alt="courtallam heritage" title="courtallam heritage" href="heritage.html" coords="1106,299,179" shape="circle">
    <area target="" alt="eco park" title="eco park" href="eco.html" coords="343,738,501,827" shape="rect">
</map>
     
     
    </body>
</html>

eco.html
<html>
    <head>
        <title>eco.html</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">TENKASI</h1>
        <h3 align="center">ECO PARK</h3>
    <p>The "Eco Park" in Tenkasi is located in Courtallam and 
        is a popular tourist spot known for its natural environment,
        making it a good place for walks, hiking, and photoshoots. It
        is a green area with amenities like a playground, making 
        it suitable for families with children. 

    </p>
    </body>
</html>

heritage.html
<html>
    <head>
        <title>heritage.html</title>
    </head>
    <body bgcolor="red">
        <h1 align="center">TENKASI</h1>
        <h3 align="center">HERITAGE</h3>
        <p>The Kuttalam Heritage" is a prominent resort and one
         of the main heritage-style accommodations near Tenkasi,
         located close to the Courtallam waterfalls. There doesn't 
         appear to be a hotel specifically named "Abot Heritage Hotel" 
         based on search results. 

        </p>
    </body>
</html>

kings.html
html>
    <head>
        <title>kings.html</title>
    </head>
    <body bgcolor="yellow">
        <h1 align="center">TENKASI</h1>
        <h3 align="center">KINGS PALACE</h3>
        <p>Kings Palace is a hotel in Tenkasi, near the new bus stand and railway station, known for being a budget-friendly option with comfortable, clean rooms. It features an in-house multi-cuisine restaurant that offers a variety of veg and non-veg dishes and provides services like room service and cab arrangements. The staff is often described as cooperative and helpful. 

        </p>
    </body>
</html>

yasuragi.html
<html>
    <head>
        <title>yasuragi.html</title>
    </head>
    <body bgcolor="orange">
        <h1 align="center">TENKASI</h1>
        <h3 align="center">YASURAGI RESORT</h3>
        <p>Yasuragi is a boutique resort in Shencottah, near Tenkasi, known for its tranquil location, luxurious rooms, and amenities like a swimming pool, garden, and on-site restaurant. It offers a serene getaway with modern comforts, including AC, free Wi-Fi, and diverse Indian/local cuisine options

        </p>
    </body>
</html>


```

## OUTPUT
![alt text](<Screenshot (34).png>)
![alt text](<Screenshot (25).png>)
![alt text](<Screenshot (26).png>)
![alt text](<Screenshot (35).png>)
![alt text](<Screenshot (28).png>)
![alt text](<Screenshot (32).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
