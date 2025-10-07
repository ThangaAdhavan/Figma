# Ex09 Event Registration Web Application
## Date:05.10.2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
Page 1:
html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <div class="rectangle"></div>
      <img class="photo" src="img/photo-1500462918059-b1a0cb512f1d-1.png" />
      <img class="rounded-rectangle" src="img/rounded-rectangle.png" />
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <div class="text-wrapper">CODE CRAKERS</div>
      <p class="div">Join our community to explore perfection in destroying errors</p>
      <div class="REGISTER-HERE">REGISTER<br />&nbsp;&nbsp;&nbsp;&nbsp;HERE</div>
      <img class="line" src="img/line-2.svg" />
      <img class="img" src="img/line-1.png" />
    </div>
  </body>
</html>

css
.android-medium {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.android-medium .rectangle {
  position: absolute;
  top: 602px;
  left: 79px;
  width: 275px;
  height: 134px;
  background-color: #d9d9d9;
}

.android-medium .photo {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 956px;
  aspect-ratio: 0.67;
  object-fit: cover;
}

.android-medium .rounded-rectangle {
  position: absolute;
  top: 602px;
  left: calc(50.00% - 143px);
  width: 275px;
  height: 134px;
}

.android-medium .text-on-a-path {
  position: absolute;
  top: 936px;
  left: 83px;
  width: 241px;
  height: 1px;
  object-fit: cover;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 67px;
  left: calc(50.00% - 122px);
  width: 313px;
  font-family: "Inter-BlackItalic", Helvetica;
  font-weight: 900;
  font-style: italic;
  color: #1e1e1e;
  font-size: 50px;
  letter-spacing: 0;
  line-height: 60px;
}

.android-medium .div {
  position: absolute;
  top: 209px;
  left: 16px;
  width: 428px;
  font-family: "Inter-BlackItalic", Helvetica;
  font-weight: 900;
  font-style: italic;
  color: #ffffff;
  font-size: 50px;
  letter-spacing: 0;
  line-height: 60px;
}

.android-medium .REGISTER-HERE {
  position: absolute;
  top: 609px;
  left: 94px;
  width: 240px;
  font-family: "Actor-Regular", Helvetica;
  font-weight: 400;
  color: #ddff00;
  font-size: 50px;
  letter-spacing: 0;
  line-height: 60px;
}

.android-medium .line {
  top: 40px;
  height: 5px;
  position: absolute;
  left: 0;
  width: 440px;
}

.android-medium .img {
  top: 206px;
  height: 6px;
  position: absolute;
  left: 0;
  width: 440px;
}

Page 2:
html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="python-programming" src="img/python-programming-language-1.png" />
      <div class="course-availability">
        Course<br />Availability<br /><br />1.Python<br /><br />2.C#<br /><br />3.Java<br /><br />4.C++
      </div>
      <p class="text-wrapper">Select a course to start</p>
      <div class="rectangle"></div>
    </div>
  </body>
</html>

css
.iphone-pro-max {
  background-color: #ffffff;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .python-programming {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 956px;
  aspect-ratio: 1.5;
  object-fit: cover;
}

.iphone-pro-max .course-availability {
  position: absolute;
  top: 132px;
  left: 62px;
  width: 319px;
  font-family: "Inter-BlackItalic", Helvetica;
  font-weight: 900;
  font-style: italic;
  color: #ffffff;
  font-size: 50px;
  letter-spacing: 0;
  line-height: 60px;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 758px;
  left: 11px;
  width: 417px;
  font-family: "Inter-BlackItalic", Helvetica;
  font-weight: 900;
  font-style: italic;
  color: #3a9734;
  font-size: 50px;
  letter-spacing: 0;
  line-height: 60px;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 93px;
  left: 48px;
  width: 333px;
  height: 647px;
  background-color: #d9d9d9;
  border-radius: 50px;
  opacity: 0.2;
}

Page 3:
html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img
        class="python-code-language"
        src="img/python-code-language-sign-programming-coding-and-developing-concept-1.png"
      />
      <p class="FINISH-THESE-LEVEL">FINISH THESE<br />LEVEL TO GET ADVANCED IN <br />PYTHON</p>
      <div class="text-wrapper">1.BEGINNER</div>
      <div class="div">2.INTERMIDIATE</div>
      <div class="text-wrapper-2">3.MASTER</div>
      <div class="rectangle"></div>
      <img class="line" src="img/line-3.svg" />
      <img class="img" src="img/line-4.svg" />
      <img class="line-2" src="img/line-5.svg" />
    </div>
  </body>
</html>

css
.iphone-pro-max {
  background-color: #ffffff;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .python-code-language {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 956px;
  aspect-ratio: 1.5;
  object-fit: cover;
}

.iphone-pro-max .FINISH-THESE-LEVEL {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  font-family: "Inter-BlackItalic", Helvetica;
  font-weight: 900;
  font-style: italic;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: 60px;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 439px;
  left: 85px;
  width: 355px;
  font-family: "Inter-BlackItalic", Helvetica;
  font-weight: 900;
  font-style: italic;
  color: #ff0000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: 60px;
}

.iphone-pro-max .div {
  position: absolute;
  top: 601px;
  left: 41px;
  width: 358px;
  font-family: "Inter-BlackItalic", Helvetica;
  font-weight: 900;
  font-style: italic;
  color: #00ff1d;
  font-size: 40px;
  letter-spacing: 0;
  line-height: 60px;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 777px;
  left: 108px;
  width: 309px;
  font-family: "Inter-BlackItalic", Helvetica;
  font-weight: 900;
  font-style: italic;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: 60px;
  white-space: nowrap;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 0;
  left: 0;
  width: 300px;
  height: 244px;
  background-color: #d9d9d9;
  border-radius: 30px;
  opacity: 0.2;
}

.iphone-pro-max .line {
  top: 501px;
  position: absolute;
  left: 0;
  width: 440px;
  height: 10px;
}

.iphone-pro-max .img {
  top: 654px;
  position: absolute;
  left: 0;
  width: 440px;
  height: 10px;
}

.iphone-pro-max .line-2 {
  top: 831px;
  position: absolute;
  left: 0;
  width: 440px;
  height: 10px;
}

Page 4:
html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="python-programming" src="img/python-programming-language-coding-development-260nw-2108069729-1.png" />
      <img class="text-on-a-path" src="img/text-on-a-path.png" />
      <img class="img" src="img/image.png" />
      <p class="text-wrapper">NAMERegister the given form to join our website</p>
      <div class="rectangle"></div>
      <img
        class="python-programming-2"
        src="img/python-programming-language-coding-development-260nw-2108069729-3.png"
      />
      <img
        class="python-programming-3"
        src="img/python-programming-language-coding-development-260nw-2108069729-2.png"
      />
      <div class="ellipse"></div>
      <p class="or-cancel-this-one">or cancel this one and <br />join other course</p>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="NAME-LEVEL-PHONE-NO">NAME:<br />LEVEL:<br />PHONE NO:<br />EMAIL:<br />FINISH REGISTERATION</div>
      <div class="rectangle-4"></div>
      <img class="line" src="img/line-8.svg" />
      <img class="line-2" src="img/line-9.svg" />
      <img class="line-3" src="img/line-6.svg" />
      <img class="line-4" src="img/line-7.svg" />
    </div>
  </body>
</html>

css
.iphone-pro-max {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .python-programming {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 394px;
  aspect-ratio: 1.39;
  object-fit: cover;
}

.iphone-pro-max .text-on-a-path {
  position: absolute;
  top: 453px;
  left: -615px;
  width: 1351px;
  height: 970px;
  object-fit: cover;
}

.iphone-pro-max .img {
  top: 357px;
  left: 0;
  width: 440px;
  height: 599px;
  position: absolute;
  aspect-ratio: 1.39;
  object-fit: cover;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 370px;
  left: calc(50.00% - 198px);
  width: 399px;
  font-family: "Inter-BlackItalic", Helvetica;
  font-weight: 900;
  font-style: italic;
  color: #00ff5d;
  font-size: 50px;
  letter-spacing: 0;
  line-height: 60px;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 566px;
  left: 39px;
  width: 368px;
  height: 390px;
  background-color: #d9d9d9;
  border-radius: 55px;
  opacity: 0.5;
}

.iphone-pro-max .python-programming-2 {
  top: 671px;
  left: 2px;
  width: 438px;
  height: 285px;
  position: absolute;
  aspect-ratio: 1.39;
  object-fit: cover;
}

.iphone-pro-max .python-programming-3 {
  top: 569px;
  left: 2px;
  width: 438px;
  height: 387px;
  position: absolute;
  aspect-ratio: 1.39;
  object-fit: cover;
}

.iphone-pro-max .ellipse {
  position: absolute;
  top: 882px;
  left: -4px;
  width: 4px;
  height: 1px;
  background-color: #000000;
  border-radius: 2px / 0.5px;
  opacity: 0.6;
}

.iphone-pro-max .or-cancel-this-one {
  position: absolute;
  top: 641px;
  left: 62px;
  width: 345px;
  font-family: "Inter-BlackItalic", Helvetica;
  font-weight: 900;
  font-style: italic;
  color: #1500ff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: 60px;
}

.iphone-pro-max .div {
  position: absolute;
  top: 883px;
  left: 0;
  width: 440px;
  height: 73px;
  background-color: #000000;
}

.iphone-pro-max .rectangle-2 {
  position: absolute;
  top: 357px;
  left: 0;
  width: 440px;
  height: 525px;
  background-color: #d9d9d9;
  opacity: 0.7;
}

.iphone-pro-max .rectangle-3 {
  position: absolute;
  top: 357px;
  left: 0;
  width: 440px;
  height: 532px;
  background-color: #000000;
}

.iphone-pro-max .NAME-LEVEL-PHONE-NO {
  position: absolute;
  top: 369px;
  left: 7px;
  width: 425px;
  font-family: "Inter-BlackItalic", Helvetica;
  font-weight: 900;
  font-style: italic;
  color: #ffffff;
  font-size: 50px;
  letter-spacing: 0;
  line-height: 60px;
}

.iphone-pro-max .rectangle-4 {
  position: absolute;
  top: 611px;
  left: 0;
  width: 440px;
  height: 123px;
  background-color: #d9d9d9;
  border-radius: 30px;
  opacity: 0.4;
}

.iphone-pro-max .line {
  position: absolute;
  top: 604px;
  left: 0;
  width: 432px;
  height: 7px;
}

.iphone-pro-max .line-2 {
  position: absolute;
  top: 546px;
  left: 0;
  width: 432px;
  height: 5px;
}

.iphone-pro-max .line-3 {
  position: absolute;
  top: 429px;
  left: 2px;
  width: 432px;
  height: 5px;
}

.iphone-pro-max .line-4 {
  position: absolute;
  top: 487px;
  left: 0;
  width: 436px;
  height: 5px;
}

Page 5:
html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <div class="rectangle"></div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper">Registered successfully</div>
      <p class="thank-you-for-co">Thank you<br />for co-operating in our site</p>
      <p class="p">Now you can attend the class according to the schedule</p>
    </div>
  </body>
</html>
 
 css
. iphone-pro-max {
background-color: #ffffff;
overflow: hidden;
width: 100%;
min-width•. 440px;
min-height: 956px;
position: relative;
}
. iphone-pro-max . rectangle {
position: absolute;
top: 0;
left: e;
width: 440px;
height: 320px;
background-color: #d9d9d9;
}
. iphone-pro-max . div {
top: 684px;
height: 272px;
position: absolute;
left: 0;
width: 440px;
background-color: #d9d9d9;
}
. iphone-pro-max . rectangle-2 {
top: 32Øpx;
height: 364px;
position: absolute;
left: 0;
width: 440px;
background-color: #d9d9d9;
}
. iphone-pro-max . text-wrapper {
position: absolute;
top: 394px;
left: 6px;
width: 440px;
font-family: "Inter-B1ackIta1ic"
font-weight: gee;
font-style: italic;
COI O r :
font-size: 64px;
letter-spacing: 0;
line-height: 60px;
.iphone-pro-max . thank-you-for-co {
position: absolute;
top: 701 px;
left: 6px;
width: 381px;
font-family: "Inter-B1ackIta1ic" ,
font-weight: gee;
font-style: italic;
color: #ffffff;
font-size: 64px;
letter-spacing: 0;
line-height: 60px;
Helvetica;
Helvetica;
}
. iphone-pro-max .p {
position: absolute;
top: 0;
left: 6px;
width: 434px;
font-family: "Inter-B1ackIta1ic" ,
font-weight: 900;
font-style: italic;
color: #ffffff;
font-size: 64px;
letter-spacing: 0;
line-height: 60px;
Helvetica;
}
```
## OUTPUT:
![alt text](<Figma/Figmaapp/static/Screenshot (11).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
