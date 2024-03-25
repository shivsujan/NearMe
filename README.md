# Ex04 Places Around Me
## Date: 22/03/2024

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
map.html
```
<html>
    <head>
        <title>puducherry</title>
    </head>02
    <body bgcolor="pink">
        <h1>Puducherry City</h1>
        <h3>Shiv Sujan S R (212223040194)</h3>
        <img src="map.png" usemap="#image-map">

        <map name="image-map">
            <area target="" alt="Primose School" title="Primose School" href="1.html" coords="633,420,396,390" shape="rect">
            <area target="" alt="Pondy Marina" title="Pondy Marina" href="2.html" coords="868,669,85" shape="circle">
            <area target="" alt="Yokohama" title="Yokohama" href="3.html" coords="564,471,767,503" shape="rect">
            <area target="" alt="Lawspet" title="Lawspet" href="4.html" coords="694,167,806,202" shape="rect">
            <area target="" alt="Primose 2" title="Primose 2" href="5.html" coords="194,405,347,422" shape="rect">
        </map>
    </body>
</html>
```
1.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="cyan">
        <h1 align="center">
        <font color="gold"><b>Puducherry</b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>Primose school</b></font>
        </h3>
        <hr size="3" color="cyan">
        <p align="justify">
        <font face="Georgia" size="5">
        
Primrose School is a nurturing and academically enriching educational institution dedicated to providing children with a strong foundation for lifelong success. With a focus on early childhood development, Primrose School offers a comprehensive curriculum designed to stimulate cognitive, social, emotional, and physical growth in young learners. Through a blend of structured learning activities, play-based exploration, and individualized attention, Primrose School creates a supportive and engaging environment where children can thrive. With a commitment to fostering creativity, critical thinking, and character development, Primrose School prepares students for future academic challenges while instilling a love of learning. Additionally, Primrose School emphasizes the importance of partnership with parents, ensuring open communication and collaboration to support each child's unique journey.






        </font>
        </p>
    </body>
</html>
```
2.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="gold">
        <h1 align="center">
        <font color="cyan"><b>Puducherry</b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>pondy Marina</b></font>
        </h3>
        <hr size="3" color="green">
        <p align="justify">
        <font face="Georgia" size="5">
            To Pondy Marina Boat House, your ultimate destination for thrilling adventure boat rides in the captivating city of Pondicherry, India. 
        
        </font>
        </p>
    </body>
</html>

```
3.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="green">
        <h1 align="center">
        <font color="cyan"><b>Puducherry</b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>Yokohama 2</b></font>
        </h3>
        <hr size="3" color="green">
        <p align="justify">
        <font face="Georgia" size="5">
            yokohama 2 is the another branch of yokohama
        </font>
        </p>
    </body>
</html>

```
4.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="silver">
        <h1 align="center">
        <font color="cyan"><b>Puducherry</b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>Lawspet</b></font>
        </h3>
        <hr size="3" color="green">
        <p align="justify">
        <font face="Georgia" size="5">
            Lawspet is a locality in the union territory of Puducherry in India. It was named after Jean Law de Lauriston
        </font>
        </p>
    </body>
</html>

```
5.html
```

<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="lightblue">
        <h1 align="center">
        <font color="cyan"><b>Puducherry</b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>primose 2</b></font>
        </h3>
        <hr size="3" color="green">
        <p align="justify">
        <font face="Georgia" size="5">
            Yokohama India in Pondicherry provides a wide range of tires for Cars, SUVs, and trucks. Find nearest wheel alignment and balancing store.
        </font>
        </p>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2024-03-22 154317.png>) ![alt text](<Screenshot 2024-03-22 153825.png>) ![alt text](<Screenshot 2024-03-22 153837.png>) ![alt text](<Screenshot 2024-03-22 153906.png>) ![alt text](<Screenshot 2024-03-22 154201.png>) ![alt text](<Screenshot 2024-03-22 154231.png>)






## RESULT
The program for implementing image maps using HTML is executed successfully.
