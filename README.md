# EXP 09 - CREATING A COMMERCIAL WEBSITE 
## AIM:

To create a commercial website using html and css.

## SOFTWARE:

Visual Studio Code.

## ALGORITHM:

1) Create a new HTML file and save it with a .html extension.Begin with the basic structure by adding the <!DOCTYPE html> declaration at the top.
2) Set up the Head:
```
       Inside the <head> element, add the <title> element and give it a meaningful title for your website.
       Link your CSS file by adding the <link> element with the rel attribute set to "stylesheet" and 
       the href attribute pointing to your CSS file.
```
3) Develop the Content:
```
        Divide the main content area into sections using appropriate HTML elements like <section>, <div>, or <article>.
        Use headings <h1> to <h6> to structure your content hierarchically.
        Incorporate text, images, videos, and other media within the content sectionS
```

4) Style with CSS:
``` 
  Create a new CSS file and save it with a .css extension.
  Select the elements you want to style using CSS selectors.
  Apply styles using properties and values. 
  For example, you can change colors, fonts, sizes, margins, and padding.
```
5) Find a web hosting provider to host your website online.
Upload your HTML, CSS, and any other necessary files to the hosting server.

6) Test your website again after deployment to ensure it works as intended.
  
## PROGRAM:
  
### HTML CODE:
  
```java
  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>webpage</title>
    <link rel="stylesheet" href="1.css"/>
</head>
<body>
    <div class="container">
        <div id="header">
            <div style="color:red ;font-size: 30px">BEST TUNING</div>
            <div style = "font-size: 30px"><a href="#"> Home</a></div>
            <div style = "font-size: 30px"><a href="#">Project</a></div>
            <div style = "font-size: 30px"><a href="#">Team</a></div>
            <div style = "font-size: 30px"><a href="#">Contact</a></div>
            <div style = "font-size: 30px"><button style="background-color: red;padding:8px;border-radius: 15px;"><a href="#">Book An Appointment</a></button>
        </div>
        
        
    </div>
    <center><img src="1.jpeg" height="500px" width="1000px;margin-top: 100px"></center>
    <div class="img">
        <p style="font-size:30px"><b><i>TUNING PERFECTION</i></b></p>
        <p style="font-size:30px"> in an upgrade that unlocks hidden<br/>potential of your car</p>
        
    </div>
    <img src="2.jpg" style="float:right;padding-left: 120px;">
    <div>
        <p style="color:white;font-size:60px">WHAT IS TUNING AND <br/>WHY DO YOU WANT IT?</p>
        <p style="text-align: justify;color:white;font-size:25px">Tuning is an upgrade to the software in the vehicle's computer.Custom software is installed that charges many parameters
        that control the way the engine operators. With proper tuning you can increase both power and fuel of economy.</p>
    </div>

    <img src="1.jpeg" height="500px" width="700px" style="float: left;padding-right:50px;">
    <div style="color:white;font-size: 20px;margin-bottom:100px;">
      
        <BR>
            <BR>
        <p style="font-size:50px">WHATCAN I EXPECT FROM TUNING?</p>
        <p style="text-align: justify;font-size:30px">What can I expect from Tuning?<br/>Through proper modification, it is possible to greatle increase the power output of the vehicle, while 
            at the same time omproving safety and longevity of the engine,drivability, and smoothness.
        </p>
        <div style="display: flex;">
            <h3 style="padding-right: 300px; font-size:30px">20-35 hp</h3>
            <h3 style="font-size:30px">35-50 hp</h3>
        </div>
        <div style="display: flex;">
            <h4 style="padding-right: 200px;font-size:30px">Roughly increase from <br/>a stage 1 tune</h4>
            <h4 style="font-size:30px">Roughly increase from <br/>a stage 2 tune</h4>
        </div>
    </div>
    <div id="footer">
        <div style="color:red ; font-size: 30px">BEST TUNING</div>
        <div style = "font-size: 30px"><a href="#">Home</a></div>
        <div style = "font-size: 30px"><a href="#">Project</a></div>
        <div style = "font-size: 30px"><a href="#">Team</a></div>
        <div style = "font-size: 30px"><a href="#">Contact</a></div>
        <div style="color:white ;font-size: 30px">&copy 2009 Best Tuning. All rights reserved.</div>
        <div style="font-size:40px"><a><b>f</b></a></div>
        <div style="font-size:40px"><a><b>in</b></a></div>
    </div>    
</body>
</html>
      
```
### CSS CODE:
      
```java
      
      body{
    background-color: black;
   margin:50px;
}

#header
{
    display:flex;
    justify-content:space-around;
}
a{
    color:white;
    
}
.img
{
    font-size:20px;
    color:white;
}
#footer
{
   display: flex;
   justify-content:space-around;
}
``` 
## OUTPUT
 
### HOME PAGE:

![image](https://github.com/Monisha-11/EXP-02-MODERN-WEB/assets/93427240/6d672bfe-bb8f-46d1-9eb8-d5156654f9ed)

  
      
### DETAILS PAGE:
<img width="1265" alt="image" src="https://github.com/Monisha-11/EXP-02-MODERN-WEB/assets/93427240/b88a7458-bc46-4ac7-a009-6fb35f2540cb">

### FOOTER:

<img width="1262" alt="image" src="https://github.com/Monisha-11/EXP-02-MODERN-WEB/assets/93427240/b73bd524-798c-46e4-90d8-148986e93066">

## RESULT:
      
Thus the website is created.
