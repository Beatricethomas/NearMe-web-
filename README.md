# Ex04 Places Around Me
## Date: 5-04-2024

## AIM
To develop a website to display details about the places around my native.

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

## PROGRAM 
```
Map.html

<html>
    <title>My City</title>
    <body bgcolor="white">
        <h1 align="center"><font color="blue"> TRIVANDRUM </font></h1>
        <h3 align="center">
            <font color="purple" size="6"> BEATRICE THOMAS (212223110005) </font></h3>
        <center>
            <img src="map.png"  usemap="#MyCity" height="750" width="1300" color="black">
            <map name="MyCity">
                    <area shape="rect" coords="1,564,236,644" href="place1.html" title="Madre De Deus Church">     
                    <area shape="rect" coords="1,337,94,388" href="place2.html" title="Veli tourist village">
                    <area shape="rect" coords="800,300,800,350" href="place3.html" title="Vikram Sarabhai Space Museum">
                    <area shape="rect" coords="77,731,1140,797,916,746" href="place4.html" title="Sree Padmanabhasamy Temple">
                    <area shape="rect" coords="384,806,665,828" href="place5.html" title="Shangumugham Beach">
            </map>
        </center>

    </body>
</html>

place1.html

<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="7"> TRIVANDRUM</font>
    </h1>
    <br>
    <h3 align="center">
        <font face="Times New Roman" color="black" size="6">Madre De Deus Church </font>
    </h3>
    <body bgcolor="cyan" align="center">
        <hr size="3" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            The Mother of God Church, also known as the Madre de Deus Church ("mother of God" in Portuguese/Latin), is a church located in Vettukad in Kerala, India's Thiruvananthapuram district. The current church building was constructed in 1934 and finished in 1937 and has since grown into a small township with a Christian population of 6,770.
        </font>
        </p>
    </body>
</html>

place2.html

<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="7"> TRIVANDRUM</font>
    </h1>
    <br>
    <h3 align="center">
        <font face="Times New Roman" color="black" size="6">Madre De Deus Church </font>
    </h3>
    <body bgcolor="cyan" align="center">
        <hr size="3" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            The Mother of God Church, also known as the Madre de Deus Church ("mother of God" in Portuguese/Latin), is a church located in Vettukad in Kerala, India's Thiruvananthapuram district. The current church building was constructed in 1934 and finished in 1937 and has since grown into a small township with a Christian population of 6,770.
        </font>
        </p>
    </body>
</html>

place3.html

<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="7"> TRIVANDRUM</font>
    </h1>
    <br>
    <h3 align="center">
        <font face="Times New Roman" color="black" size="6">Vikram Sarabhai Space Museum</font>
    </h3>
    <body bgcolor="pink" align="center">
        <hr size="3" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            The Vikram Sarabhai Space Centre (VSSC) is a major space research centre of the Indian Space Research Organisation (ISRO), focusing on rocket and space vehicles for India's satellite programme.It is located in Trivandrum, in the Indian state of Kerala.
            The centre had its beginnings as the Thumba Equatorial Rocket Launching Station (TERLS) in 1962. It was renamed in honour of Vikram Sarabhai, often regarded as the father of the Indian space program. H.G.S. Murthy was appointed as the first director of Thumba Equatorial Rocket Launching Station.
        </font>
        </p>
    </body>
</html>

place4.html

<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="7"> TRIVANDRUM</font>
    </h1>
    <br>
    <h3 align="center">
        <font face="Times New Roman" color="black" size="6"> Sree Padmanabhasamy Temple </font>
    </h3>
    <body bgcolor="green" align="center">
        <hr size="3" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            The Padmanabhaswamy Temple is a Hindu temple, dedicated to Vishnu, in Thiruvananthapuram, the capital of the state of Kerala, India. It is one of the 108 Divya Desams, the sacred abodes of Vishnu in the Sri Vaishnava tradition. It is widely considered as the world's richest Hindu temple.The name of the city of 'Thiruvananthapuram' in Malayalam and Tamil translates to "The City of Ananta" (Ananta being a form of Vishnu).
        </font>
        </p>
    </body>
</html>

place5.html

<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="7"> TRIVANDRUM</font>
    </h1>
    <br>
    <h3 align="center">
        <font face="Times New Roman" color="black" size="6"> Shangumugham Beach </font>
    </h3>
    <body bgcolor=" yellow " align="center">
        <hr size="3" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Shankumugham Beach is a beach in Thiruvananthapuram district of Kerala, south India. The beach is on the western side of Thiruvananthapuram (Trivandrum) and is very close to Trivandrum International Airport.Shanghumugham beach is considered as the Arattukadavu of Sri Ananthapadmanabhan - the presiding deity of the city. 
        </font>
        </p>
    </body>
</html>
```


## OUTPUT







## RESULT
The program for implementing image maps using HTML is executed successfully.
