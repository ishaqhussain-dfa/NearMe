# Ex04 Places Around Me
## Date: 
16/04/2024

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
<html lang="en">
    <head>
    </head>
    <script>
        function coordinate(event)
        {
            let x = event.clientX;
            let y = event.clientY;
            document.getElementById("text1").value = x;
            document.getElementById("text2").value = y;
        }
    </script>
    <body>
        <img src="map1.png" width="1000px" usemap="#MapNew" onmousemove="coordinate(event)"> <br>
        <MAP name="MapNew">
            <AREA shape="RECT" coords="536,158,551,176" href="https://www.zomato.com/chennai/brews-beyond-nungambakkam"
            Title="Brews & Beyond">
            <AREA shape="RECT" coords="638,369,651,380" href="https://www.zomato.com/chennai/tukaway-nungambakkam"
            Title="Tukaway">
            <AREA shape="RECT" coords="285,217,200,238" href="https://www.zomato.com/chennai/lafayette-by-mug-cakes-nungambakkam"
            Title="Lafayette">
            <AREA shape="RECT" coords="591,254,602,271" href="https://www.zomato.com/chennai/scoobys-cafe-nungambakkam"
            Title="Scooby's cafe">
            <AREA shape="RECT" coords="850,72,862,93" href="https://www.zomato.com/chennai/barrocco-nungambakkam"
            Title="Barrocco">
            <AREA shape="RECT" coords="208,63,219,85" href="https://www.zomato.com/chennai/darjeeling-cafe-1-nungambakkam"
            Title="Darjeeling cafe">
        </MAP>
        x Co-ordinate <input type="text" name="" id="text1" style="font-size:medium;"><br>
        y Co-ordinate <input type="text" name="" id="text2" style="font-size: medium;">
    </body>            
</html>
```
## OUTPUT
![image](https://github.com/Naveenaa28/NearMe/assets/131433133/38c25f66-e2f1-469a-b4aa-f99087acc163)

![image](https://github.com/Naveenaa28/NearMe/assets/131433133/3a6a6921-3e44-4990-b8b7-8cb42d2f8686)


## RESULT
The program for implementing image maps using HTML is executed successfully.
