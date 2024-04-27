
## Date: 10-04-2024

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

# 0-map.html
```
<html>
<head>
<title>~Chennai~</title>
</head>
<body>
<h1 align="center"><b> Chennai </b></h1>
<h3 align="center"><b> ARJUN N S(212223230020)</b></h3>
<center>
<img src="map.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
    <area alt="Arjun's Home" title="Arjun's Home" href="home.html" coords="779,138,804,157" shape="rect">
    <area alt="Hussain Memorial School" title="Hussain Memorial School" href="myschool.html" coords="816,123,836,140" shape="rect">
    <area alt="Chennai,Marina Beach" title="Chennai,Marina Beach" href="marina.html" coords="1294,374,1438,403" shape="rect">
    <area alt="Saveetha Engineering College" title="Saveetha Engineering College" href="mycollege.html" coords="281,477,354,511" shape="rect">
    <area alt="Pachaiamman Temple" title="Pachaiamman Temple" href="localtemple.html" coords="516,52,728,91" shape="rect">
</map>
</center>
</body>
</html>
```

# 1-home.html
```
<html>
<head>
<title>My Home</title>
</head>
<body bgcolor="black">
<h1 align="center" style="color: white;"><b>Chennai</b></h1>
<h3 align="center" style="color: white;"><b>My Home</b></h3>
<hr size="3" color="white">
<p align="center" style="color: white;">
<font face="Georgia" size="5" color="white">
1) Nestled in a vibrant suburban community, the area surrounding my home exudes a sense of warmth and friendliness, with tree-lined streets and well-maintained sidewalks.<br>
2) The neighborhood boasts convenient access to essential amenities such as grocery stores, schools, parks, and recreational facilities, making daily errands and leisure activities easily accessible.<br>
3) Residents in the area share a strong sense of community spirit, often coming together for neighborhood events, block parties, and other social gatherings, fostering a welcoming and inclusive atmosphere.<br>
</p>
<div style="text-align: center;">
    <img src="home.png" width="1200" height="500">
</div>
</body>
</html>
```

# 2-myschool.html
```
<html>
<head>
<title>My School</title>
</head>
<body bgcolor="black">
<h1 align="center" style="color: white;"><b>Chennai</b></h1>
<h3 align="center" style="color: white;"><b>My School</b></h3>
<hr size="3" color="white">
<p align="center" style="color: white;">
<font face="Georgia" size="5" color="white">
1) My school is a small local school filled with memories of my childhood.<br>
2) Eventhough it might be small it's a very decent School.<br>
3) It is a friendly school filled with teachers who give a good amount of freedom.<br>
</p>
<div style="text-align: center;">
    <img src="school.png" width="1200" height="500">
</div>
</body>
</html>
```

# 3-marina.html
```
<html>
<head>
<title>Marina Beach</title>
</head>
<body bgcolor="black">
<h1 align="center" style="color: white;"><b>Chennai</b></h1>
<h3 align="center" style="color: white;"><b>Marina Beach</b></h3>
<hr size="3" color="white">
<p align="center" style="color: white;">
<font face="Monaco" size="5" color="white">
1) This is the second largest beach in the world, located at India, TamilNadu, Chennai.<br>
2) A good Basic beach.<br>
3) the food in this beach is really good, it is kind of messy due to bad garbage handling.<br>
</p>
<div style="text-align: center;">
    <img src="marina.png" width="1200" height="500">
</div>
</body>
</html>
```

# 4-mycollege.html
```
<html>
<head>
<title>My College</title>
</head>
<body bgcolor="black">
<h1 align="center" style="color: white;"><b>Chennai</b></h1>
<h3 align="center" style="color: white;"><b>My College</b></h3>
<hr size="3" color="white">
<p align="center" style="color: white;">
<font face="Monaco" size="5" color="white">
1) I just completed my first sem on this college.<br>
2) A good College with a good amount offreedom provided, not very pressury like other colleges.<br>
3) Friendly Staffs.<br>
</p>
<div style="text-align: center;">
    <img src="college.png" width="1200" height="500">
</div>
</body>
</html>
```

# 5-localtemple.html
```
<html>
<head>
<title>Local Temple</title>
</head>
<body bgcolor="black">
<h1 align="center" style="color: white;"><b>Chennai</b></h1>
<h3 align="center" style="color: white;"><b>Local Temple</b></h3>
<hr size="3" color="white">
<p align="center" style="color: white;">
<font face="Monaco" size="5" color="white">
1) A big temple with a peaceful ambience to walk in, and visit the gods.<br>
2) I've been here when i was young, i used to go there with my mom.<br>
3) Helps find peace.<br>
</p>
<div style="text-align: center;">
    <img src="localtemple.png" width="1200" height="500">
</div>
</body>
</html>
```
## OUTPUT:
![Screenshot 2024-04-27 102534](https://github.com/sowmya-badoni/NearMe/assets/152136324/8fbd36d8-2b2b-4728-9870-eab01f07d279)
![Screenshot 2024-04-27 102548](https://github.com/sowmya-badoni/NearMe/assets/152136324/8c87ca9c-56cf-42b8-8836-ffb3f1201ce8)
![Screenshot 2024-04-27 102611](https://github.com/sowmya-badoni/NearMe/assets/152136324/0f223124-20b3-462a-b834-9c905275b9cc)
![Screenshot 2024-04-27 102623](https://github.com/sowmya-badoni/NearMe/assets/152136324/2cad9ab6-f1e4-4fa3-b95e-4f8b2d8f9d74)
![Screenshot 2024-04-27 102634](https://github.com/sowmya-badoni/NearMe/assets/152136324/572854cc-5293-4d11-8f87-067500483f7b)




## RESULT
The program for implementing image maps using HTML is executed successfully.
