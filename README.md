# Ex04 Places Around Me
## Date: 07-12-2024

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

map.html
<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font colour="red"><b>Senneerkuppam</b></font>
</h1>
<h3 align="center">
<font colour="blue"><b>S.Ravant Vignesh (24900151)</b></font>
</h3>
<center>
<img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="My home town" title="My home town" href="home.html" coords="753,306,989,507" shape="rect">
    <area target="" alt="hospital" title="hospital" href="hospital.html" coords="1223,371,1341,420" shape="rect">
    <area target="" alt="college" title="college" href="college.html" coords="461,11,660,65" shape="rect">
    <area target="" alt="church" title="church" href="church.html" coords="562,754,310,666" shape="rect">
    <area target="" alt="restaurant" title="restaurant" href="restaurant.html" coords="916,656,1157,727" shape="rect">
</map>
</map>
</map>
</center>
</body>
</html>

church.html

<html>
<head>
<title>My Home Town</title>
</head>
<body style="background-color: red;">
<h1 align="center">
<font color="red"><b>Senneerkuppam</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>CSI-WESLEY CHURCH</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="georgia" size="5">
CSI WESLY is the famous church
it is located in senneerkuppam
it is a peaceful place
it has an important role in history during india's freedom 
</font>
</p>
</body>
</html>

college.html

<html>
<head>
<title>My Home Town</title>
</head>
<body style="background-color: yellow;">
<h1 align="center">
<font color="red"><b>Senneerkuppam</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>SA college</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="georgia" size="5">
    S.A.Engineering College offers the students with advantageous atmosphere with state-of-the-art facilities, distinguished mentors, and pleasant educational environment. 
    The institution provides the employability and communication skills for the development of students. It provides quality education in an environment of discipline.
     The focus is on shaping students to become self-disciplined, self-dependent and self-confident individuals. 
     SAEC pulls out all the stops to mould the students’ career in such a way that they excel in all fine distinction of life. 
</p>
</body>
</html>

home.html

<html>
<head>
<title>My Home Town</title>
</head>
<body style="background-color: pink;">
<h1 align="center">
<font color="red"><b>Senneerkuppam</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>tiruneermalai-devotional centre</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="georgia" size="5">
The Thiruneermalai temple complex consists of two temples,
the Ranganatha Temple and the Thiruneermalai Neervanna Perumal Temp
Both are Hindu temples in Thiruneermalai,
a suburb of Chennai, Tamil Nadu, India.
There are two temples, one at the top of the hill and other in th
</p>
</body>
</html>

home.html

<html>
<head>
<title>My Home Town</title>
</head>
<body style="background-color: pink;">
<h1 align="center">
<font color="red"><b>Senneerkuppam</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>tiruneermalai-devotional centre</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="georgia" size="5">
The Thiruneermalai temple complex consists of two temples,
the Ranganatha Temple and the Thiruneermalai Neervanna Perumal Temp
Both are Hindu temples in Thiruneermalai,
a suburb of Chennai, Tamil Nadu, India.
There are two temples, one at the top of the hill and other in th
</p>
</body>
</html>

hospital.html

<html>
<head>
<title>My Home Town</title>
</head>
<body style="background-color: aqua;">
<h1 align="center">
<font color="red"><b>Senneerkuppam</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>ACS HOSPITAL</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="georgia" size="5">
    Being a developing nation, health and hygiene are mainstays in terms of national priority.
     With so many people living below the poverty line, statistics reveal that unhealthy living conditions will lead to disease and epidemics, unless a proactive approach by the medical community is put into action. 
     Keeping these in mind, Dr.M.G.R.Educational and Research Institute, Deemed to be University has established A.C.S.Medical College and hospital in 2008. 
     Besides imparting necessary medical and technological skills,
</p>
</body>
</html>

restaurant.html

<html>
<head>
<title>My Home Town</title>
</head>
<body style="background-color: blueviolet;">
<h1 align="center">
<font color="red"><b>Senneerkuppam</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Restaurant</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="georgia" size="5">
Hana restaurant & cafe is a restaurant located in Chennai, Tamil Nadu.
 The average rating of this place is 4.50 out of 5 stars based on 124 reviews.
  The street address of this place is 102/1, Poonamallee High Road, Goparasanallur, Poonamallee, Chennai, Tamil Nadu 600102, India.
 It is about 3.03 kilometers away from the Alappakkam railway station.
</p>
</body>
</html>


```

## OUTPUT
![alt text](<Screenshot (55).png>)
![alt text](<Screenshot (56).png>)
![alt text](<Screenshot (57).png>)
![alt text](<Screenshot (58).png>)
![alt text](<Screenshot (59).png>)
![alt text](<Screenshot (60).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
