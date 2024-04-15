# Ex04 Places Around Me
## Date: 15.04.2024

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
    <title>MY CITY</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b> SIRKAZHI</b></font>
         </h1>
         <h3 align="center">
            <font color="blue"><b> LOGESH.N.A (212223240078)</b></font>
         </h3>
         <center>
            <img src="Screenshot 2024-04-15 191015.png" usemap="#MYCITY" height="600" width="1450">
            <map name="MYCITY">
                <area shape="rect" coords="800,350,850,400" href="foundation.html" title="ABDUL KALAM FOUNDATION">
                <area shape="rect" coords="700,400,800,480" href="school.html" title="VISION SCHOOL">
                <area shape="rect" coords="820,300,880,350" href="temple.html" title="SIRKAZHI SATTAINATHAR TEMPLE ">
                <area shape="rect" coords="830,200,950,300" href="hotel.html" title="RAJAMSELVA HOTEL">
                <area shape="rect" coords="700,480,750,520" href="home.html" title="MY HOME">
            </map>
         </center>
    </body>
</html>

foundation.html
<html>
<head>
<title>ABDUL KALAM FOUNDATION</title>

</head>

<body bgcolor ="cyan">
<h1 align="center" >
<font color="red"><b>SIRKAZHI</b></font>
</h1>
<h2 align="center">
<font color="blue"><b>ABDUL KALAM FOUNDATION</b></font>
</h2>
<hr size="3" color="yellow">
<p align="justify">
<font face="Georgia" size="4">
<i><u><h>ABDUL KALAM FOUNDATION:</i></u></h>
<u1>
    Kalam Foundation is a Trust, registered under Indian Trust Act, 1882 inspired by of Former President, Bharat Ratna
     Dr. APJ Abdul Kalam, dedicated to the integrated & sustainable development of India according Dr.Kalam dream through
      the intervention of science, engineering and technology. Kalam Foundation today has 15 state units and a few overseas
       units as well. Eminent scientists, academicians, policy makers, and social workers are the torch bearers of the vision 
       of Dr. APJ Abdul Kalam.
</font>




</p>
</body>
</head>
</html>

school.html
<html>
<head>
<title>My Home Town</title>
</head>

<body bgcolor="pink">
<h1 align="center" >
<font color="red"><b>SIRKAZHI</b></font>
</h1>
<h2 align="center">
<font color="green"><b>SCHOOL</b></font>
</h2>
<hr size="3" color="blue">
<p align="justify">
<font face="Georgia" size="4">
<i><u><h>VISION SCHOOL:</i></u></h>
<u1>
     
     Vision School is located in Thenpathi, Sirkali.
     The human mind is the most delicate, complicated, yet powerful weapon the human race has ever seen. 
     The best minds in the world are those of children. During school age, the thirst for knowledge would be humongous. 
     Cultivating the right knowledge and practices in these young minds would pave an extraordinary path for a successful future.

<u1>

</font>
</p>
</body>
</head>
</html>

temple.html
<html>
<head>
<title>My Home Town</title>
</head>

<body bgcolor="yellow">
<h1 align="center" >
<font color="red"><b>SIRKAZHI</b></font>
</h1>
<h2 align="center">
<font color="green"><b>TEMPLE</b></font>
</h2>
<hr size="3" color="blue">
<p align="justify">
<font face="Georgia" size="4">
<i><u><h>SIRKAZHI SATTAINATHAR TEMPLE:</i></u></h>
<u1>

    Sattainathar temple, Sirkazhi (also called Brahmapureeswarar temple and Thoniappar temple) is a Hindu temple
     dedicated to Shiva located in Sirkali, Tamil Nadu, India. The temple is incarnated by the hymns of Thevaram
      and is classified as Paadal Petra Sthalam. 
      It is an ancient temple complex with three different Shiva shrines in three stories.

    The Bhramapureeswarar shrine is housed in the lower level. Brahmapureeswarar is accompanied by Ambal Sthira
     sundari/Thiripurasundari or Thirunilainayaki in Tamil. The second-level houses Periyanakar with Periyanayaki on a Thoni, 
     hence the name Thoniappar. Sattainathar/Vatukanathar is also housed here. There are 22 water bodies associated with this shrine.
      Three different forms of Shiva are worshipped here, the Shivalingam (Bhrammapureeswarar), a colossal image of Uma Maheswarar
       (Toniappar) at the medium level, and Bhairavar (Sattanathar) at the upper level. The temple is associated with the legend of 
       child Sambandar who is believed to have been fed by Parvathi on the banks of the temple tank. The child later went on to compose
        Tevaram, a Saiva canonic literature on Shiva and became one of the most revered Saiva poets in South India.
</u1>



</font>
</p>
</body>
</head>
</html>


hotel.html
<html>
<head>
<title>My Home Town</title>
</head>

<body bgcolor="orange">
<h1 align="center" >
<font color="red"><b>Sirkazhi</b></font>
</h1>
<h2 align="center">
<font color="blue"><b>HOTEL</b></font>
</h2>
<hr size="3" color="green">
<p align="justify">
<font face="Georgia" size="4">
<i><u><h>RAJAMSELVA HOTEL:</i></u></h>

<u1>

    A hotel is an establishment that provides paid lodging on a short-term basis. 
    Facilities provided inside a hotel room may range from a modest-quality mattress in a small room to large suites with bigger, 
     higher-quality beds, a dresser, a refrigerator, and other kitchen facilities, upholstered chairs, a flat-screen television, 
     and en-suite bathrooms. Small, lower-priced hotels may offer only the most basic guest services and facilities. 
     Larger, higher-priced hotels may provide additional guest facilities such as a swimming pool, a business center with computers, 
     printers, and other office equipment, childcare, conference and event facilities, tennis or basketball courts, gymnasium,
      restaurants, day spa, and social function services.

    Boasting a terrace, HOTEL RAJAM SELVA is situated in Sirkazhi. 
    This 4-star hotel offers room service and a 24-hour front desk. 
    The nearest airport is Puducherry Airport, 88 km from the hotel.
    </u1>
</font>
</p>
</body>
</head>
</html>

home.html
<html>
<head>
<title>My Home Town</title>
</head>

<body bgcolor="lavender">
<h1 align="center" >
<font color="red"><b>SIRKAZHI</b></font>
</h1>
<h2 align="center">
<font color="purple"><b>HOME</b></font>
</h2>
<hr size="3" color="blue">
<p align="justify">
<font face="Georgia" size="4">
<i><u><h>MY HOME :</i></u></h>
<u1>

Home is a safe haven and a comfort zone. 
A place to live with our families and pets and enjoy with friends.
 A place to build memories as well as a way to build future wealth.
  A place where we can truly just be ourselves.
My house is my most favourite place in the world.
     I live with my mother and father in my house. 
    My house has three floors and lots of stairs.
     We have a garden outside our house with beautiful flowers.
    Maybe the reason you can never go home again is that, once you're back, you can never leave.

<u1>


</font>
</p>
</body>
</head>
</html>

```

## OUTPUT
![map (1)](https://github.com/Logesh051/NearMe/assets/144979188/42c3f807-04e7-4cfd-9a47-0d2899e30afd)

![foundation](https://github.com/Logesh051/NearMe/assets/144979188/1d08159c-8e76-4ea7-82ba-64a82c78723c)

![school](https://github.com/Logesh051/NearMe/assets/144979188/13cecc09-60d1-4ccf-b7c3-89e6da523749)

![temple](https://github.com/Logesh051/NearMe/assets/144979188/af4a6c5f-d9bd-4718-af42-873e8d35b14b)

![hotel](https://github.com/Logesh051/NearMe/assets/144979188/c3986f1b-a837-4f2d-8bce-0b4a206eacb9)

![homw](https://github.com/Logesh051/NearMe/assets/144979188/4094f6e2-7975-46af-9f1f-8a11b7ee0863)

## RESULT
The program for implementing image maps using HTML is executed successfully.
