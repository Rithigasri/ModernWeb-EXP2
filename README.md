# EXPERIMENT 02: CREATE A COMMERCIAL WEBSITE USING HTML AND CSS
## AIM:
To create a commercial website using html and css.
## ALGORITHM:
1. Create basic html page.
2. Use div components to separate each section of the webpage.
3. Add css styling to the required components.
4. Link the css file inside the head tag of html file.
5. Run the html page and dsiplay the output.
## PROGRAM:
### car.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CARS</title>
    <link rel="stylesheet" href="car.css"/>
</head>
<body>
    <div class="container">
        <div id="header" style="font-size: 20px;">
            <div style="color:red">BEST TUNING</div>
            <div><a href="#">Home</a></div>
            <div><a href="#">Project</a></div>
            <div><a href="#">Team</a></div>
            <div><a href="#">Contact</a></div>
            <div><button style="background-color: red;padding:8px;border-radius: 15px;">
            <a href="#">Book An Appointment</a></button>
        </div>
        
        
    </div>
    <center><img src="https://www.bugatti.com/fileadmin/_processed_/sei/p329/se-image-87f40fb0b7981f56cc3f3c7f4dd788c2.jpg" 
    height="500px" width="1000px;"></center>
    <div class="img">
        <p style="color:crimson"><b><i>TUNING PERFECTION</i></b></p>
        <p >Tuning in an upgrade that unlocks hidden<br/>potential of your car</p>
        <p><a href="#" style="color:red">Explore more</a></p>
    </div>
    <img src="https://c4.wallpaperflare.com/wallpaper/144/104/1013/black-gauges-dash-macro-speedometer-hd-wallpaper-preview.jpg" 
    style="float:right;padding-left: 120px;">
    <div>
        <p style="color:white;padding-top: 50px;font-size: 25px;"><b>WHY DO YOU WANT IT?</b></p>
        <p style="color:white;font-size:60px">What is Tuning and <br/>Why do You Want It?</p>
        <p style="text-align: justify;color:white;font-size:25px">
        Tuning is an upgrade to the software in the vehicle's computer.Custom software is installed that charges many parameters
        that control the way the engine operators. With proper tuning you can increase both power and fuel of economy.</p>
    </div>
    <div style="display:inline;">
        <img src="https://i.pinimg.com/originals/f8/df/6d/f8df6d060cb54b2271a7e77f543085ae.jpg" 
        height="100px" width="100px" style="padding-right:80px">
        <img src="pic.png" width="100px" height="110px">
    </div>
    <div style="display:flex;color:white">
        <div style="padding-right: 30px;"><p>A comprehensive tool<br/>for high horsepower<br/>builds.</p></div>
        <div><p>With proper tuning,<br/>you can increase fuel<br/>economy.</p></div>
    </div>
    <img src="https://static.designboom.com/wp-content/uploads/2021/10/rolls-royce-black-badge-ghost-car-designboom01.jpg" 
    height="500px" width="700px" style="float: left;padding-right:50px;">
    <div style="color:white;font-size: 20px;margin-bottom:100px;">
        <h3 ><b>ADVANTAGES</b></h3>
        <p style="font-size:50px">What can I Expect from Tuning?</p>
        <p style="text-align: justify;">What can I expect from Tuning?<br/>Through proper modification, 
        it is possible to greatle increase the power output of the vehicle, while 
            at the same time omproving safety and longevity of the engine,drivability, and smoothness.
        </p>
        <div style="display: flex;">
            <h3 style="padding-right: 300px;">20-35 hp</h3>
            <h3>35-50 hp</h3>
        </div>
        <div style="display: flex;">
            <h4 style="padding-right: 200px;">Roughly increase from <br/>a stage 1 tune</h4>
            <h4 >Roughly increase from <br/>a stage 2 tune</h4>
        </div>
    </div>
    <div id="footer">
        <div style="color:red">BEST TUNING</div>
        <div><a href="#">Home</a></div>
        <div><a href="#">Project</a></div>
        <div><a href="#">Team</a></div>
        <div><a href="#">Contact</a></div>
        <div style="color:white">&copy 2009 Best Tuning. All rights reserved.</div>
        <div style="font-size:25px"><a><b>f</b></a></div>
        <div style="font-size:25px"><a><b>in</b></a></div>
    </div>
</body>
</html>
```
### car.css
```
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

## OUTPUT:
![image](https://github.com/Rithigasri/ModernWeb-EXP2/assets/93427256/94a492fe-8da9-40ce-943f-70ea31274bec)
![image](https://github.com/Rithigasri/ModernWeb-EXP2/assets/93427256/2ece2368-2377-4465-b4d8-90835ed0c656)
![image](https://github.com/Rithigasri/ModernWeb-EXP2/assets/93427256/e4135b4a-5816-4f16-9c7c-ad7ea5718c3b)

## RESULT:
Thus,a commercial website is created using html and css.

