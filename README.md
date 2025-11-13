# Ex:09 Event Registration Web Application
## Date: 13.11.2025

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
```
homepage.html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="frame">
      <img class="element" src="img/177-1.png" />
      <div class="text-wrapper">Code Craft-2025</div>
      <div class="a-hands-on-tech">A Hands-On Tech<br />&nbsp;&nbsp;&nbsp;&nbsp;Workshop</div>
      <img class="images" src="img/images-1-1.png" />
      <div class="rectangle"></div>
      <p class="register-now">
        <span class="span">Register</span>
        <span class="text-wrapper-2">&nbsp;</span>
        <span class="span">now</span>
      </p>
      <img class="img" src="img/rectangle-9.svg" />
      <img class="logo" src="img/logo-1.png" />
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

homepage.css
.frame {
  overflow: hidden;
  background: linear-gradient(
      0deg,
      rgba(0, 0, 0, 0.2) 0%,
      rgba(0, 0, 0, 0.2) 100%
    ), linear-gradient(180deg, rgba(0, 229, 255, 1) 0%, rgba(0, 0, 0, 1) 100%);
  width: 100%;
  min-width: 360px;
  min-height: 640px;
  position: relative;
}

.frame .element {
  position: absolute;
  top: 0;
  left: 0;
  width: 360px;
  height: 640px;
  aspect-ratio: 1.78;
  object-fit: cover;
}

.frame .text-wrapper {
  position: absolute;
  top: calc(50.00% - 235px);
  left: calc(50.00% - 180px);
  width: 404px;
  font-family: "Krona One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .a-hands-on-tech {
  position: absolute;
  top: 139px;
  left: 72px;
  width: 214px;
  -webkit-text-stroke: 1px #4f2f2f;
  font-family: "Koulen-Regular", Helvetica;
  font-weight: 400;
  color: #a74c9e;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .images {
  position: absolute;
  top: 248px;
  left: 73px;
  width: 201px;
  height: 251px;
  aspect-ratio: 0.8;
  object-fit: cover;
}

.frame .rectangle {
  position: absolute;
  top: 541px;
  left: 81px;
  width: 193px;
  height: 47px;
  background-color: #ff5454;
  border: 1px solid;
  border-color: #000000;
  box-shadow: inset 0px 4px 4px #00000040;
}

.frame .register-now {
  position: absolute;
  top: 546px;
  left: 107px;
  width: 178px;
  font-family: "Merge One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .span {
  font-family: "Merge One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
}

.frame .text-wrapper-2 {
  font-size: 32px;
}

.frame .img {
  position: absolute;
  top: 0;
  left: 0;
  width: 360px;
  height: 54px;
}

.frame .logo {
  position: absolute;
  top: 0;
  left: 0;
  width: 360px;
  height: 55px;
  aspect-ratio: 6.65;
  object-fit: cover;
}

frame2.html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="frame">
      <img class="abstract-geometric" src="img/abstract-geometric-background-in-flat-design-free-vector-1.png" />
      <div class="div"></div>
      <div class="rectangle"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="rectangle-6"></div>
      <div class="text-wrapper">register form</div>
      <img class="age" src="img/age.svg" />
      <img class="register-no" src="img/register-no.svg" />
      <img class="clear-all" src="img/clear-all.svg" />
      <img class="register" src="img/register.svg" />
      <img class="department" src="img/department.svg" />
      <img class="name" src="img/name.svg" />
      <img class="e-mail" src="img/e-mail.svg" />
    </div>
  </body>
</html>

global2.css
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

style2.css
.frame {
  background-color: #ff7676;
  width: 100%;
  min-width: 360px;
  min-height: 640px;
  position: relative;
}

.frame .abstract-geometric {
  position: absolute;
  top: 73px;
  left: 0;
  width: 360px;
  height: 567px;
  aspect-ratio: 1.56;
  object-fit: cover;
}

.frame .div {
  position: absolute;
  top: 457px;
  left: 180px;
  width: 131px;
  height: 36px;
  background-color: #fd6161;
  box-shadow: inset 0px 4px 4px #00000040;
}

.frame .rectangle {
  position: absolute;
  top: 457px;
  left: 26px;
  width: 128px;
  height: 36px;
  background-color: #fd5f5f;
  box-shadow: inset 0px 4px 4px #00000040;
}

.frame .rectangle-2 {
  position: absolute;
  top: 345px;
  left: 0;
  width: 330px;
  height: 38px;
  background-color: #d9d9d9;
}

.frame .rectangle-3 {
  position: absolute;
  top: 297px;
  left: 0;
  width: 330px;
  height: 33px;
  background-color: #d9d9d9;
}

.frame .rectangle-4 {
  position: absolute;
  top: 242px;
  left: 0;
  width: 330px;
  height: 32px;
  background-color: #d9d9d9;
}

.frame .rectangle-5 {
  position: absolute;
  top: 182px;
  left: 0;
  width: 330px;
  height: 36px;
  background-color: #d9d9d9;
}

.frame .rectangle-6 {
  position: absolute;
  top: 126px;
  left: 3px;
  width: 327px;
  height: 33px;
  background-color: #d9d9d9;
}

.frame .text-wrapper {
  position: absolute;
  top: 20px;
  left: 0;
  font-family: "Nosifer-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .age {
  position: absolute;
  top: 246px;
  left: 13px;
  width: 50px;
  height: 24px;
}

.frame .register-no {
  position: absolute;
  top: 301px;
  left: 14px;
  width: 141px;
  height: 24px;
}

.frame .clear-all {
  position: absolute;
  top: 467px;
  left: 192px;
  width: 102px;
  height: 17px;
}

.frame .register {
  position: absolute;
  top: 466px;
  left: 41px;
  width: 92px;
  height: 23px;
}

.frame .department {
  position: absolute;
  top: 356px;
  left: 14px;
  width: 144px;
  height: 24px;
}

.frame .name {
  position: absolute;
  top: 132px;
  left: 14px;
  width: 72px;
  height: 19px;
}

.frame .e-mail {
  position: absolute;
  top: 189px;
  left: 14px;
  width: 77px;
  height: 19px;
}

frame3.html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="frame">
      <img class="geometric-abstract" src="img/geometric-abstract-2560x2560-23187-2.png" />
      <img class="img" src="img/geometric-abstract-2560x2560-23187-1.png" />
      <div class="thank-you-for">Thank you for&nbsp;&nbsp;registering!</div>
      <p class="we-are-eagerly">we are eagerly waiting for your&nbsp;&nbsp; participation</p>
    </div>
  </body>
</html>
 globals3.css
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

style3.css
.frame {
  background-color: #ffffff;
  width: 100%;
  min-width: 360px;
  min-height: 640px;
  position: relative;
}

.frame .geometric-abstract {
  top: 0;
  left: 0;
  width: 360px;
  height: 640px;
  position: absolute;
  aspect-ratio: 1;
  object-fit: cover;
}

.frame .img {
  top: 140px;
  left: 34px;
  width: 292px;
  height: 292px;
  position: absolute;
  aspect-ratio: 1;
  object-fit: cover;
}

.frame .thank-you-for {
  position: absolute;
  top: 83px;
  left: 15px;
  font-family: "Post No Bills Jaffna ExtraBold-Regular", Helvetica;
  font-weight: 400;
  color: #948aff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .we-are-eagerly {
  position: absolute;
  top: 441px;
  left: 75px;
  width: 251px;
  font-family: "Racing Sans One-Regular", Helvetica;
  font-weight: 400;
  color: #ff4e4e;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}




```


## OUTPUT:
![alt text](<fundwe 9 ss.jpg>)


## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
