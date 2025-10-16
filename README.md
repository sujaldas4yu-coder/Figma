# Ex09 Event Registration Web Application
## Date:16.10.2025

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
slide 1

index.html
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
      <img class="sports" src="img/sports1-1.png" />
      <div class="rectangle"></div>
      <img class="img" src="img/rectangle-4.svg" />
      <div class="text-wrapper">RESGISTER</div>
      <div class="div">LOGIN</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-2">SPORTS DAY EVENT</div>
      <img class="SEC-LOGO" src="img/SEC-LOGO-1.png" />
    </div>
  </body>
</html>

global.css
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css
.android-medium {
  background-color: #ffffff;
  width: 100%;
  min-width: 700px;
  min-height: 840px;
  position: relative;
}

.android-medium .sports {
  position: absolute;
  top: 0;
  left: 0;
  width: 700px;
  height: 840px;
  aspect-ratio: 1.73;
  object-fit: cover;
}

.android-medium .rectangle {
  position: absolute;
  top: 691px;
  left: 42px;
  width: 235px;
  height: 99px;
  background-color: #ffffff82;
}

.android-medium .img {
  position: absolute;
  top: 691px;
  left: 398px;
  width: 283px;
  height: 99px;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 712px;
  left: 425px;
  font-family: "Jua-Regular", Helvetica;
  font-weight: 400;
  color: #170505;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .div {
  position: absolute;
  top: 712px;
  left: 92px;
  width: 135px;
  font-family: "Jua-Regular", Helvetica;
  font-weight: 400;
  color: #030000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .rectangle-2 {
  position: absolute;
  top: 249px;
  left: 71px;
  width: 549px;
  height: 89px;
  background-color: #ffffffb8;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 265px;
  left: 118px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .SEC-LOGO {
  position: absolute;
  top: 0;
  left: 0;
  width: 700px;
  height: 188px;
  aspect-ratio: 3.79;
  object-fit: cover;
}

slide 2

index.html
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
      <img class="sports" src="img/sports3-1.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">sports day event</div>
      <div class="div">cricket</div>
      <div class="text-wrapper-2">football</div>
      <div class="text-wrapper-3">baseball</div>
      <div class="text-wrapper-4">hockey</div>
      <div class="text-wrapper-5">badminton</div>
      <img class="star" src="img/star-1.svg" />
      <img class="img" src="img/star-2.svg" />
      <img class="star-2" src="img/star-3.svg" />
      <img class="star-3" src="img/star-4.svg" />
      <img class="star-4" src="img/star-5.svg" />
      <div class="rectangle-2"></div>
      <div class="text-wrapper-6">designed by: sujal das(25013553)</div>
    </div>
  </body>
</html>

global.css
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css
.android-medium {
  background-color: #ffffff;
  width: 100%;
  min-width: 565px;
  min-height: 678px;
  position: relative;
}

.android-medium .sports {
  position: absolute;
  top: 0;
  left: 0;
  width: 565px;
  height: 678px;
  aspect-ratio: 1;
  object-fit: cover;
}

.android-medium .rectangle {
  position: absolute;
  top: 29px;
  left: 46px;
  width: 476px;
  height: 77px;
  background-color: #d9d9d94c;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 44px;
  left: 78px;
  font-family: "Luckiest Guy-Regular", Helvetica;
  font-weight: 400;
  color: #210808;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .div {
  position: absolute;
  top: 153px;
  left: 78px;
  font-family: "Love Ya Like A Sister-Regular", Helvetica;
  font-weight: 400;
  color: #ff0004;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 309px;
  left: 79px;
  font-family: "Love Ya Like A Sister-Regular", Helvetica;
  font-weight: 400;
  color: #ff0004;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 228px;
  left: 78px;
  width: 214px;
  font-family: "Love Ya Like A Sister-Regular", Helvetica;
  font-weight: 400;
  color: #ff0004;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .text-wrapper-4 {
  position: absolute;
  top: 479px;
  left: 85px;
  font-family: "Love Ya Like A Sister-Regular", Helvetica;
  font-weight: 400;
  color: #ff0000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-5 {
  position: absolute;
  top: 394px;
  left: 79px;
  font-family: "Love Ya Like A Sister-Regular", Helvetica;
  font-weight: 400;
  color: #ff0004;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .star {
  top: 169px;
  left: 34px;
  position: absolute;
  width: 26px;
  height: 25px;
}

.android-medium .img {
  top: 243px;
  left: 34px;
  position: absolute;
  width: 26px;
  height: 25px;
}

.android-medium .star-2 {
  top: 407px;
  left: 34px;
  position: absolute;
  width: 26px;
  height: 25px;
}

.android-medium .star-3 {
  top: 494px;
  left: 34px;
  position: absolute;
  width: 26px;
  height: 25px;
}

.android-medium .star-4 {
  top: 319px;
  left: 38px;
  position: absolute;
  width: 26px;
  height: 25px;
}

.android-medium .rectangle-2 {
  position: absolute;
  top: 583px;
  left: 19px;
  width: 528px;
  height: 73px;
  background-color: #d9d9d94a;
}

.android-medium .text-wrapper-6 {
  position: absolute;
  top: 603px;
  left: 85px;
  width: 406px;
  font-family: "Mogra-Regular", Helvetica;
  font-weight: 400;
  color: #1b0606;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

slide 3

index.html

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
      <img class="sports" src="img/sports2-1.png" />
      <div class="text-wrapper">REGISTRATION FORM</div>
      <div class="div">NAME :</div>
      <div class="text-wrapper-2">AGE :</div>
      <div class="text-wrapper-3">GENDER :</div>
      <div class="text-wrapper-4">REGISTRATION NO. :</div>
      <div class="text-wrapper-5">DEPARTMENT :</div>
      <p class="p">DESIGNED BY : SUJAL DAS (25013553)</p>
      <div class="text-wrapper-6">EMAIL ID :</div>
      <div class="text-wrapper-7">MOBILE NO:</div>
      <div class="text-wrapper-8">FILL YOUR DETAILS</div>
    </div>
  </body>
</html>


global.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.android-medium {
  background-color: #ffffff;
  width: 100%;
  min-width: 569px;
  min-height: 686px;
  position: relative;
}

.android-medium .sports {
  position: absolute;
  top: 0;
  left: 0;
  width: 569px;
  height: 686px;
  aspect-ratio: 1.33;
  object-fit: cover;
}

.android-medium .text-wrapper {
  top: 22px;
  left: 145px;
  color: #000000;
  font-size: 24px;
  position: absolute;
  font-family: "Ibarra Real Nova-Regular", Helvetica;
  font-weight: 400;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .div {
  position: absolute;
  top: 105px;
  left: 67px;
  font-family: "Ibarra Real Nova-Regular", Helvetica;
  font-weight: 400;
  color: #a40a0a;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 147px;
  left: 67px;
  font-family: "Ibarra Real Nova-Regular", Helvetica;
  font-weight: 400;
  color: #ae0808;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 189px;
  left: 70px;
  font-family: "Ibarra Real Nova-Regular", Helvetica;
  font-weight: 400;
  color: #c91414;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-4 {
  top: 231px;
  left: 64px;
  color: #c51c1c;
  font-size: 20px;
  position: absolute;
  font-family: "Ibarra Real Nova-Regular", Helvetica;
  font-weight: 400;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-5 {
  position: absolute;
  top: 273px;
  left: 62px;
  font-family: "Ibarra Real Nova-Regular", Helvetica;
  font-weight: 400;
  color: #d91e1e;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .p {
  position: absolute;
  top: 641px;
  left: 79px;
  font-family: "Kyiv*Type Serif-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .text-wrapper-6 {
  position: absolute;
  top: 315px;
  left: 64px;
  font-family: "Kyiv*Type Serif-Regular", Helvetica;
  font-weight: 400;
  color: #c81616;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .text-wrapper-7 {
  position: absolute;
  top: 356px;
  left: 64px;
  font-family: "Kyiv*Type Serif-Regular", Helvetica;
  font-weight: 400;
  color: #ce1313;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .text-wrapper-8 {
  position: absolute;
  top: 69px;
  left: 186px;
  font-family: "Ibarra Real Nova-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
}

```

## OUTPUT:
![alt text](image.png)
![alt text](<Screenshot 2025-10-15 054023.png>)
![alt text](<Screenshot 2025-10-16 091218.png>)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
