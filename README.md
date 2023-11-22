# Ex04 Places Around Me
## Date: 

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
<html>
<title>trichy map</title>
<center>
<h3> 
<font color="red"><b>TRICHY</b></font>
 </h3>

<h4> 
<font color="orange"><b>GAJALAKSHMI</b> </font>
 </h4>
<h5> 
<font color="light green"><b> (23011881) </b></font>
</h5>


<img src="img.jpg" width="1500" height="650" usemap="#trichymap">

<map name="trichymap">

<area  shape="rectangle"  coords="650,400,800,550"  href ="Uchi Pillaiyar Kovil.html"  title="uchi pillayar kovil" >
<area  shape="rectangle"  coords="790,50,900,100"  href ="Srirangam.html"  title="srirangam" >
<area  shape="rectangle"  coords="950,250,1050,300"  href ="Kaveri River.html"  title="kaveri" >
<area  shape="CIRCLE"  coords="500,120,50,"  href ="Teppakulam.html"  title="teppakulam" >
<area  shape="CIRCLE"  coords="670,330,70,"  href ="Chathiram.html"  title="Chathiram bus stand" >

</map>
<body>
</body>
</html>

Chathiram.html
<html>
<body bgcolor="pink">
<h2 align="center"> CHATHIRAM BUS STAND </h2>
Chathiram Bus Stand, Tiruchirappalli, old name Chinnaiya Pillai Chathiram also popularly known Chathiram Perundu Nilayam or Chathiram Bus Stand, is one of the bus termini of Trichy, other being the Central Bus Stand.
Chinnaiya Pillai Chathiram (Choultry) Choultry is a resting place, an inn or caravansary for travelers, pilgrims or visitors to a site.
This 'D'-graded terminus, taking its name from the nearby Chinnaiya Pillai Chathiram,[2] became functional since 1979 and officially recognised in 2005.
The terminus prominently featured in Tamil Film, Sathiram Perundhu Nilayam (2013).
</body>
</html>

Kaveri River.html

<html>
<body bgcolor="skyblue">
<h2 align="center"> KAVERI RIVER </h2>
           In ancient Tamil literature,the river was also called Ponni(the golden mother,in refrence to the fine silt it deposits).
The Kaver is a sacred river to the people of southern India and isworkshipped as the GoddessKaveriamma(Mother Cauvery).It is
considered to be among the seven holy rivers of india.
</body>
</html>

Srirangam.html

<html>
<body bgcolor="orange">
<h2 align="center"> SRIRANGAM </h2>
Sri Ranganathaswamy Temple is a Hindu temple dedicated to Ranganatha (a form of Vishnu), located in Srirangam, Tiruchirapalli, Tamil Nadu, India.
It is the most illustrious Vaishnava temples in South India rich in legend and history.
The Deity finds a mention in the great Sanskrit epic Ramayana which is dated around 800 to 400 BCE which also pushes the existence of deity to the same era,which shows that the temple is minimum 2500 to 3000 years old archeologically and traditionally 30 lakh years old.
</body>
</html>

Teppakulam.html

<html>
<body bgcolor="cyan">
<h2 align="center"> TEPPAKULAM </h2>
Trichy Teppakulam is an ancient water tank located in Trichy, Tamil Nadu, India. It was built by King Thirumalai Nayak in the 17th century (1645) and is one of the largest tanks in India. The tank covers an area of about 5 acres and is surrounded by a stone wall.
Teppakulam is a locality near the centre of the Indian city of Tiruchirappalli. It consists of a large artificial tank surrounded by bazaars, prominent among which is a flower market.It contains the Thayumanavar Temple and the Sri Naganathar Swamy Temple, the St. Joseph College Church and Holy Cross Church, and Srimathi Indira Gandhi College for Women.The historic Rockfort is situated nearby.A large monolithic figure of Ganesh, Mukkuruni Vinayaka, was reportedly found during an excavation of the Mariamman Teppakulam tank.The Teppam Floating Festival is held here on boats in January or February and it is a common time and place for marriages.
</body>
</html>

Uchi Pillaiyar Kovil.html

<html>
<body bgcolor="yellow">
<h2 align="center"> UCHI PILLAIYAR TEMPLE </h2>
<h3 align="center"> (ROCKFORT) </h3>
This temple is beleived to have been constructed in the 6th century by Mahendra Varman of Pallava dynasty.The fort is also known as Pillaiyar Kovil and 
draws huge footfalls during the Chittiraifestivel,celabratedin the months of April and May for 15 days.
</body>
</html>

```
## OUTPUT
![Alt text](maps4-1.png)
![Alt text](1-1.png)
![Alt text](2-1.png)
![Alt text](3-1.png)
![Alt text](4-1.png)
![Alt text](5-1.png)

## RESULT
The program for implementing image maps using HTML is executed successfully.
