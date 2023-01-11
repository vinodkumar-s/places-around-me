# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:
Step 1:
Create a new django project and app

Step 2:
Type code in views and urls.py

Step 3:
create HTML files according to your places

Step 4:
Give deatils about that places in html file

Step 3:
Run the server.

## Code:
```html
<!DOCTYPE html>
<html>
    <head>
        <title>RESORT MAP</title>
        </head>
        <body>
             <img src="/static/images/map1.jpg" height="884" width="1684" usemap="#resortmap">
             <MAP name="resortmap">
                 <AREA shape="RECT" coords="154,444,301,558"
                       href="/OceanSprayResort/" Title="OceanSprayResort">
                 <AREA shape="RECT" coords="573,384,656,547"
                       href="/swimmingpool/"Title="swimmingpool">

                 <AREA shape="RECT" coords="38,610,224,770"
                       href="/carparking/"Title="carparking">

                <AREA shape="RECT"  coords="537,784,874,687"
                       href="/rooms/"Title="rooms">

                <AREA shape="RECT" coords="203,130,274,408"
                        href="/dininghall/"Title="dininghall">
             </MAP>
    
            
        </body>

</html>

```

## Output:
![output](/map%20(2).png)

![output](/html%20checker.png)


## Result:
Thus a website is developed to display details about the places around my house.