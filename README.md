# Ex03 Places Around Me
## Date: 05/12/2025

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

##CODE


```
<html>
   <head>
    <title>My city</title>
   </head>
    <body> 
            <h2 align="center" textcolor="white">PONNAMARAVATHI</h2>
            <br></br>
            <h4 align="center" textcolor="blue">LOGESH S</h4>
        
            <img src="Screenshot 2025-11-28 113617.png" usemap="#image-map">

                <map name="image-map">
                    <area target="" alt="Ponnamaravathi" title="Ponnamaravathi" href="pon.html" coords="779,483,719,216,1074,241,1170,345,1133,362,990,423" shape="poly">
                    <area target="" alt="Poolankuruchi" title="Poolankuruchi" href="pool.html" coords="231,398,172" shape="circle">
                    <area target="" alt="Melaisivapur" title="Melaisivapur" href="mel.html" coords="261,799,512,631" shape="rect">
                    <area target="" alt="J.J nagar" title="J.J nagar" href="jj.html" coords="895,621,85" shape="circle">
                    <area target="" alt="Vegupatti" title="Vegupatti" href="veg.html" coords="1271,325,1392,349,1375,529,1195,483,1212,399" shape="poly">
                </map>
    </body>
</html> 

<html>
<head>
<title>J.J</title>
</head>
<body bgcolor="dark blue">
    <h2 align="center" textcolor="black">Ponnamaravathi City</h2>
    <h4 align="center" textcolor="yellow">J.J</h4>
    <hr>
    <p>
        JJ Nagar is a locality within or near Ponnamaravathi, a significant town and Taluk (sub-district) in the Pudukkottai District of Tamil Nadu, India, known for its local businesses like J J Aqua Minerals and historical sites like the ancient Thiruvizha Temple. Ponnamaravathi is about 37 km from the district headquarters, Pudukkottai, and is a historically rich area with a mix of agriculture and small-scale industries, attracting visitors to its cultural heritage
</body>
</html>

<html>
<head>
<title>Melaisivapur</title>
</head>
<body bgcolor="grey">
    <h2 align="center" textcolor="black">Piranmalai City</h2>
    <h4 align="center" textcolor="pink">Melaisivapur</h4>
    <hr>
    <p>
        Melaisivapuri is a Panchayat village within the Ponnamaravathi Taluk (Block) in the Pudukkottai District, Tamil Nadu, known for its temples like the Aathi Ponnalagi Amman Temple, serving as a local spiritual hub with rural infrastructure, while Ponnamaravathi itself is a larger town, the taluk headquarters, rich in heritage and housing numerous surrounding villages, all part of the historically significant Pudukkottai region. 
    </p>
</body>
</html>

<html>
<head>
<titlePonnamaravathi</title>
</head>
<body bgcolor="green">
    <h2 align="center" textcolor="orange">Ponnamaravathi City</h2>
    <h4 align="center" textcolor="purple">Ponnamaravathi</h4>
    <hr>
    <p>
        Ponnamaravathi is a significant Town Panchayat and Taluk in the Pudukkottai District of Tamil Nadu, India, known for its rich history, culture, and proximity to Chettinad heritage sites, featuring temples like Karpaka Vinayakar & Kundrakkudi Murugan, historical forts like Thirumayam, and famous Athangudi Palace Tiles. It's a hub for local administration, education, and a gateway to exploring traditional Tamil culture, with a warm, oppressive climate. 
    </p>
</body>
</html>

<html>
<head>
<title>Poolankuruchi</title>
</head>
<body bgcolor="brown">
    <h2 align="center" textcolor="black">Poolankuruchi village</h2>
    <h4 align="center" textcolor="red">Poolankuruchi</h4>
    <hr>
    <p>
       Poolankurichi (பூலாங்குறிச்சி) is a village (Gram Panchayat) in the Tiruppattur taluk of the Sivaganga District, Tamil Nadu, India, known for its community harmony, local governance, and proximity to significant temples like the Thiruthalinathar Temple in nearby Tiruppattur. It's part of the Sivaganga Lok Sabha constituency, with a population of over 3,000 as per the 2011 census, featuring friendly inter-community relations. 
 
    </p>
</body>
</html>

<html>
<head>
<title>Vegu</title>
</head>
<body bgcolor="navy blue">
    <h2 align="center" textcolor="white">Vegupatti village</h2>
    <h4 align="center" textcolor="green">Vegu</h4>
    <hr>
    <p>
        Vegupatti is a village located in the Pudukkottai district of Tamil Nadu, India, and is notable for being near several temples, including the Viswaroopa Anjeneyar Temple and the Maruthu Vinayagar Temple. The village can be reached from Chennai by flying to a nearby airport and then taking a taxi, or by taking a train or bus, though train travel is faster than the bus. 
    </p>
</body>
</html>
```
## OUTPUT
![alt text](<Screenshot 2025-12-05 091209-5.png>)
![alt text](<Screenshot 2025-12-05 091355.png>)
![alt text](<Screenshot 2025-12-05 091444.png>) 
![alt text](<Screenshot 2025-12-05 091245.png>)
![alt text](<Screenshot 2025-12-05 091501.png>)
![alt text](<Screenshot 2025-12-05 091322.png>)



## RESULT
The program for implementing image maps using HTML is executed successfully.


