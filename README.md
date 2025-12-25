# Ex08 Event Registration Web Application
## Date:24.12.2025

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:
page1.html
```
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
      <img class="screenshot" src="img/screenshot-2025-12-24-172607-1.png" />
      <img class="img" src="img/screenshot-2025-12-24-172756-1.png" />
      <img class="screenshot-2" src="img/screenshot-2025-12-24-171923-1.png" />
      <div class="text-wrapper">ANNUAL SPORTS EVENT</div>
      <div class="rectangle"></div>
      <div class="div">ANNUAL SPORTS EVENT</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-2">login</div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-3">register</div>
    </div>
  </body>
</html>
```
page1.css
```
.iphone-pro-max {
  background-color: #9fb3b9;
  overflow: hidden;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .screenshot {
  position: absolute;
  top: 974px;
  left: 464px;
  width: 13px;
  height: 10px;
  aspect-ratio: 1.25;
  object-fit: cover;
}

.iphone-pro-max .img {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 956px;
  aspect-ratio: 0.67;
  object-fit: cover;
}

.iphone-pro-max .screenshot-2 {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 88px;
  aspect-ratio: 5.02;
  object-fit: cover;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 356px;
  left: calc(50.00% - 360px);
  width: 12px;
  font-family: "Holtwood One SC-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 13px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 222px;
  left: 15px;
  width: 333px;
  height: 95px;
  background-color: #c9c8d0;
}

.iphone-pro-max .div {
  position: absolute;
  top: 243px;
  left: 45px;
  width: 222px;
  font-family: "Holtwood One SC-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .rectangle-2 {
  position: absolute;
  top: 533px;
  left: 22px;
  width: 143px;
  height: 59px;
  background-color: #d9d9d9;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 550px;
  left: 65px;
  font-family: "Holtwood One SC-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-3 {
  position: absolute;
  top: 638px;
  left: 15px;
  width: 179px;
  height: 76px;
  background-color: #143acf;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 663px;
  left: 55px;
  font-family: "Holtwood One SC-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}
```
page2.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro">
      <img class="screenshot" src="img/screenshot-2025-12-24-172756-2.png" />
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <div class="text-wrapper">e</div>
      <div class="rectangle"></div>
      <div class="outdoor-events">outdoor<br />events</div>
      <div class="div"></div>
      <div class="text-wrapper-2">cricket</div>
      <img class="star" src="img/star-1.svg" />
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <img class="img" src="img/star-2.svg" />
      <img class="star-2" src="img/star-3.svg" />
      <img class="star-3" src="img/star-4.svg" />
      <div class="text-wrapper-3">foot ball</div>
      <div class="text-wrapper-4">volley ball</div>
      <div class="text-wrapper-5">basket ball</div>
    </div>
  </body>
</html>
```
page2.css
```
.iphone-pro {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 521px;
  min-height: 949px;
  position: relative;
}

.iphone-pro .screenshot {
  position: absolute;
  top: 0;
  left: 0;
  width: 521px;
  height: 949px;
  aspect-ratio: 0.67;
  object-fit: cover;
}

.iphone-pro .text-on-a-path {
  position: absolute;
  top: 44px;
  left: -440px;
  width: 307px;
  height: 94px;
}

.iphone-pro .text-wrapper {
  position: absolute;
  top: 112px;
  left: 160px;
  font-family: "Holtwood One SC-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .rectangle {
  position: absolute;
  top: 52px;
  left: 17px;
  width: 350px;
  height: 181px;
  background-color: #eee7e7;
}

.iphone-pro .outdoor-events {
  position: absolute;
  top: 78px;
  left: 56px;
  font-family: "Holtwood One SC-Regular", Helvetica;
  font-weight: 400;
  color: #141313;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .div {
  position: absolute;
  top: 324px;
  left: 47px;
  width: 249px;
  height: 58px;
  background-color: #d9d9d9;
}

.iphone-pro .text-wrapper-2 {
  position: absolute;
  top: 334px;
  left: 125px;
  width: 215px;
  font-family: "Holtwood One SC-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .star {
  position: absolute;
  top: 331px;
  left: 55px;
  width: 42px;
  height: 39px;
}

.iphone-pro .rectangle-2 {
  position: absolute;
  top: 449px;
  left: 47px;
  width: 249px;
  height: 58px;
  background-color: #d9d9d9;
}

.iphone-pro .rectangle-3 {
  position: absolute;
  top: 585px;
  left: 47px;
  width: 249px;
  height: 61px;
  background-color: #d9d9d9;
}

.iphone-pro .rectangle-4 {
  position: absolute;
  top: 741px;
  left: 47px;
  width: 249px;
  height: 58px;
  background-color: #d9d9d9;
}

.iphone-pro .img {
  position: absolute;
  top: 449px;
  left: 57px;
  width: 46px;
  height: 47px;
}

.iphone-pro .star-2 {
  position: absolute;
  top: 590px;
  left: 57px;
  width: 46px;
  height: 51px;
}

.iphone-pro .star-3 {
  position: absolute;
  top: 744px;
  left: 52px;
  width: 48px;
  height: 50px;
}

.iphone-pro .text-wrapper-3 {
  position: absolute;
  top: 461px;
  left: 125px;
  font-family: "Holtwood One SC-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .text-wrapper-4 {
  position: absolute;
  top: 598px;
  left: 111px;
  width: 199px;
  font-family: "Holtwood One SC-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .text-wrapper-5 {
  position: absolute;
  top: 753px;
  left: 114px;
  font-family: "Holtwood One SC-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}
```
page3.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro">
      <img class="screenshot" src="img/screenshot-2025-12-24-172756-3.png" />
      <div class="rectangle"></div>
      <div class="indoor-events">indoor<br />events</div>
      <img class="star" src="img/star-5.svg" />
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <img class="img" src="img/star-6.svg" />
      <img class="star-2" src="img/star-7.svg" />
      <div class="rectangle-3"></div>
      <img class="star-3" src="img/star-8.svg" />
      <div class="text-wrapper">chess</div>
      <div class="text-wrapper-2">carrom</div>
      <div class="text-wrapper-3">tennis</div>
    </div>
  </body>
</html>
```
page3.css
```
.iphone-pro {
  background-color: #ffffff;
  width: 100%;
  min-width: 478px;
  min-height: 940px;
  position: relative;
}

.iphone-pro .screenshot {
  position: absolute;
  top: 0;
  left: 0;
  width: 478px;
  height: 940px;
  aspect-ratio: 0.67;
  object-fit: cover;
}

.iphone-pro .rectangle {
  top: 27px;
  left: 7px;
  width: 297px;
  height: 157px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone-pro .indoor-events {
  position: absolute;
  top: 51px;
  left: 71px;
  font-family: "Holtwood One SC-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .star {
  position: absolute;
  top: 407px;
  left: 114px;
  width: 3px;
  height: 2px;
}

.iphone-pro .div {
  top: 431px;
  left: 37px;
  width: 252px;
  height: 65px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone-pro .rectangle-2 {
  top: 555px;
  left: 36px;
  width: 240px;
  height: 62px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone-pro .img {
  position: absolute;
  top: 450px;
  left: 41px;
  width: 41px;
  height: 35px;
}

.iphone-pro .star-2 {
  position: absolute;
  top: 561px;
  left: 45px;
  width: 33px;
  height: 44px;
}

.iphone-pro .rectangle-3 {
  top: 283px;
  left: 36px;
  width: 239px;
  height: 65px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone-pro .star-3 {
  position: absolute;
  top: 295px;
  left: 45px;
  width: 40px;
  height: 38px;
}

.iphone-pro .text-wrapper {
  position: absolute;
  top: 295px;
  left: 111px;
  font-family: "Holtwood One SC-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .text-wrapper-2 {
  position: absolute;
  top: 450px;
  left: 105px;
  font-family: "Holtwood One SC-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .text-wrapper-3 {
  position: absolute;
  top: 569px;
  left: 104px;
  font-family: "Holtwood One SC-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}
```
page4.html
```
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
      <img class="screenshot" src="img/screenshot-2025-12-24-172756-4.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">name</div>
      <div class="div"></div>
      <div class="text-wrapper-2">reg no</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-3">department</div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="rectangle-6"></div>
      <div class="rectangle-7"></div>
      <div class="text-wrapper-4">event</div>
      <div class="text-wrapper-5">team members</div>
      <div class="text-wrapper-6">contact</div>
      <div class="text-wrapper-7">year</div>
      <div class="text-wrapper-8">mentor</div>
      <div class="rectangle-8"></div>
      <div class="text-wrapper-9">submit</div>
    </div>
  </body>
</html>
```
page4.css
```
.box {
  width: 3090px;
  height: 5884px;
}

.box .group {
  position: fixed;
  top: -64px;
  left: 0;
  width: 3090px;
  height: 5884px;
  display: flex;
}

.box .iphone {
  width: 3090px;
  height: 5884px;
  position: relative;
  background-color: #ffffff;
  overflow: hidden;
}

.box .iphone-pro-max {
  position: absolute;
  top: -52px;
  left: -47px;
  width: 440px;
  height: 956px;
  background-color: #ffffff;
}

.box .web {
  position: absolute;
  top: 64px;
  left: 0;
  width: 3090px;
  height: 5820px;
  aspect-ratio: 0.67;
}

.box .text-on-a-path {
  position: absolute;
  top: 3040px;
  left: -146px;
  width: 1526px;
  height: 717px;
}

.box .rectangle {
  position: absolute;
  top: 501px;
  left: 372px;
  width: 1099px;
  height: 286px;
  background-color: #d9d9d9;
}

.box .div {
  position: absolute;
  top: 1075px;
  left: 369px;
  width: 1102px;
  height: 287px;
  background-color: #d9d9d9;
}

.box .rectangle-2 {
  position: absolute;
  top: 1614px;
  left: 393px;
  width: 1173px;
  height: 271px;
  background-color: #d9d9d9;
}

.box .img {
  position: absolute;
  top: 2173px;
  left: 413px;
  width: 1173px;
  height: 280px;
}

.box .rectangle-3 {
  position: absolute;
  top: 2804px;
  left: 381px;
  width: 1213px;
  height: 258px;
  background-color: #d9d9d9;
}

.box .TEAM-MEMBER {
  position: absolute;
  top: 2861px;
  left: 463px;
  font-family: "Jacques Francois-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 128px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.box .rectangle-4 {
  position: absolute;
  top: 3413px;
  left: 381px;
  width: 1202px;
  height: 280px;
  background-color: #d9d9d9;
}

.box .rectangle-5 {
  position: absolute;
  top: 4069px;
  left: 404px;
  width: 1168px;
  height: 272px;
  background-color: #d9d9d9;
}

.box .text-wrapper {
  top: 4118px;
  left: 629px;
  position: absolute;
  font-family: "Jacques Francois-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 128px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.box .rectangle-6 {
  position: absolute;
  top: 4629px;
  left: 444px;
  width: 1071px;
  height: 265px;
  background-color: #d9d9d9;
}

.box .text-wrapper-2 {
  top: 4677px;
  left: 681px;
  position: absolute;
  font-family: "Jacques Francois-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 128px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.box .rectangle-7 {
  position: absolute;
  top: 5292px;
  left: 1062px;
  width: 1190px;
  height: 323px;
  background-color: #d9d9d9;
}

.box .text-wrapper-3 {
  position: absolute;
  top: 5369px;
  left: 1347px;
  font-family: "Jacques Francois-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 128px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.box .text-wrapper-4 {
  top: 546px;
  left: 705px;
  position: absolute;
  font-family: "Jacques Francois-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 128px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.box .REG-NO {
  position: absolute;
  top: 1134px;
  left: 624px;
  font-family: "Jacques Francois-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 128px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.box .text-wrapper-5 {
  position: absolute;
  top: 1654px;
  left: 478px;
  font-family: "Jacques Francois-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 128px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.box .text-wrapper-6 {
  position: absolute;
  top: 2229px;
  left: 725px;
  font-family: "Jacques Francois-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 128px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.box .text-wrapper-7 {
  position: absolute;
  top: 3460px;
  left: 784px;
  font-family: "Jacques Francois-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 128px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}
```
## OUTPUT:
![alt text](<Screenshot 2025-12-24 221905.png>)


## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
