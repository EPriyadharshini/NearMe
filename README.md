# Ex04 Places Around Me
## Date: 
19/11/2023
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
<title>image map</title>
<center>
<h3>name of city </h3>

<img src="img.png" width="1500" height="650" usemap="#imgmap">

<map name="imgmap">

  <area  shape="rectangle"  coords="750,550,880,650"  href ="place1.html"  title="Kanur" >
<area  shape="rectangle"  coords="300,250,450,350"  href ="place2.html"  title="vellar" >
<area  shape="rectangle"  coords="700,300,900,350"  href ="place3.html"  title="kudalaythur" >
<area  shape="circle"  coords="900,500,100"  href="place4.html"  title="munniyappar temple">
<area  shape="circle"  coords="1300,100,100"  href="place5.html"  title="mariamman temple">

</map>
<body>
</body>
</html>
 

 place1.html

 <html>
<head>
<title>Kanur</title>
</head>
<body style="background-color:aquamarine">
    <h1 align="center">
    <font color="red"><b>Kanur</b></font>
</h1>
<h3 align="center">
    <font color="blue"><b>Kanur</b></font>
</h3>
<hr size="3" color="blue">
<p align="justify">
    <font face="Georgia" size="5">
         A place in chennai filled with colours of emotion.
         Every dawn heralds a symphony of chirping crickets and the soft hum of daily activities.
         Villagers, connected by bonds woven over generations,engage in the gentle rhythm of daily chores and shared laughter.
         The simplicity of their lives mirrors the richness found in genuine relationships and shared moments  
         making the simple village a sanctuary of contentment and undisturbed joy.

    </font>
</p>
</h3>
</body>
</html>

place2.html
<html>
<head>
<title>Kanur</title>
</head>
<body style="background-color:aquamarine">
    <h1 align="center">
    <font color="black"><b>vellar</b></font>
</h1>
<h3 align="center">
    <font color="white"><b>vellar</b></font>
</h3>
<hr size="3" color="blue">
<p align="justify">
    <font face="Georgia" size="5">
        The river loks nice and make peaceful  sounds
        river is a natural flowing watercourse.
        usually a freshwater stream, flowing on the earth's land surface or inside caves towards another waterbody at a lower elevation.
        such as an ocean, sea, bay, lake, wetland, or another river.
        In some cases, a river flows into the ground or becomes dry at the end of its course without reaching another body of water.
        Small rivers can be referred to by names such as creek, brook, and rivulet. 
    </font>
</p>
</h3>
</body>
</html>

place3.html
<html>
<head>
<title>Kanur</title>
</head>
<body style="background-color:aquamarine">
    <h1 align="center">
    <font color="black"><b>kudalaythur</b></font>
</h1>
<h3 align="center">
    <font color="white"><b>kudalaythur</b></font>
</h3>
<hr size="3" color="blue">
<p align="justify">
    <font face="Georgia" size="5">
        kudalayathur is a Village in Keerapalayam Block in Cuddalore District of Tamil Nadu State, India.
         It is located 56 KM towards South from District head quarters Cuddalore. nearby Keerapalayam. 
         State capital Chennai
        kudalaythur postal head office is Vriddhachalam .
        Perundurai , B.athanur , Srinedunchery , Peruvarappur , Kottumulai 
        are the nearby Villages to kudalaythur.
        kudalaythur is surrounded by Kammapuram Block towards North , Melbhuvanagiri Block towards East , 
         Andimadam Block towards west , Kattumannarkoil Block towards South .
         Neyveli , Virudhachalam , Parangipettai , Sirkali are the near by Cities to Gudalaiyathur.
        It is near to bay of bengal. There is a chance of humidity in the weather.
       few river connected place called kudalaythur
    </font>
</p>
</h3>
</body>
</html>

place4.html
<html>
<head>
<title>Kanur</title>
</head>
<body style="background-color:aquamarine">
    <h1 align="center">
    <font color="red"><b>munniyappar</b></font>
</h1>
<h3 align="center">
    <font color="blue"><b>munniyappar</b></font>
</h3>
<hr size="3" color="blue">
<p align="justify">
    <font face="Georgia" size="5">
    the Arulmigu Vennankodi munniyappar Swamy Temple in kanur ,cuddalore, Tamil Nadu,
    The temple is dedicated to Lord Muniyappan, who is considered to be a form of Lord Shiva 
     The temple is open 24 hours a day and is known for its daily three-time puja, which is performed to the deity 
      The temple is also famous for its annual festival, which is celebrated with great enthusiasm by devotees 
    </font>
</p>
</h3>
</body>
</html>

place5.html
<html>
<head>
<title>mariamman</title>
</head>
<body style="background-color:aquamarine">
    <h1 align="center">
    <font color="red"><b>mariamman</b></font>
</h1>
<h3 align="center">
    <font color="blue"><b>mariamman</b></font>
</h3>
<hr size="3" color="blue">
<p align="justify">
    <font face="Georgia" size="5">
       The origin of mariamman in terms of a consistent and coherent legend has not been standardised, but several myths of the mother goddess exist in several regional traditions that are spread orally throughout South India.
        According to a regional Hindu legend, there was once a beautiful woman named Nagavalli, wife to a rishi named Piruhu
    </font>
</p>
</h3>
</body>
</html>
```

## OUTPUT
<img width="845" alt="map" src="https://github.com/EPriyadharshini/NearMe/assets/144870831/56804198-d285-4d85-ba55-4a40221b62d6">
<img width="960" alt="2023-11-24 (9)" src="https://github.com/EPriyadharshini/NearMe/assets/144870831/b457fcd5-9062-4872-96fb-bad82f0c5b16">
<img width="960" alt="2023-11-24 (8)" src="https://github.com/EPriyadharshini/NearMe/assets/144870831/fb32e6d2-9736-4ebc-bc88-779234ce1ff0">
<img width="960" alt="2023-11-24 (6)" src="https://github.com/EPriyadharshini/NearMe/assets/144870831/dcc67cc7-8707-4851-a0c2-c8fbe756a35a">
<img width="960" alt="2023-11-24 (5)" src="https://github.com/EPriyadharshini/NearMe/assets/144870831/a628c158-1760-485f-959b-bcc7560ed1c2">
<img width="960" alt="2023-11-24 (4)" src="https://github.com/EPriyadharshini/NearMe/assets/144870831/9f2799dd-8f26-4f84-9174-0db3b3cbd50d">

## RESULT
The program for implementing image maps using HTML is executed successfully.
