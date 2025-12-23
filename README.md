# Ex09 Event Registration Web Application
# Date:
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:Page 1:
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
    <div class="android-large">
      <img class="nebula" src="img/nebula1-1.png" />
      <img class="SEC-logo" src="img/SEC-logo-1-1.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">REGISTER</div>
      <img class="img" src="img/rectangle.svg" />
      <div class="div">LOGIN</div>
      <div class="ellipse"></div>
      <div class="text-wrapper-2">Nebula Nights</div>
    </div>
  </body>
</html>

globals.css

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


Page 2:
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
    <div class="android-large">
      <img class="nebula" src="img/nebula-1.png" />
      <div class="text-wrapper">Agenda:</div>
      <p class="DJ-nights-live-music">
        <span class="span">*</span>
        <a
          href="https://www.google.com/search?sca_esv=69afb27cda6b1637&rlz=1C1GCEA_en-GB&cs=0&sxsrf=AE3TifOpY1-XUZJ6mZYSH_y2c1LRCiMpdA%3A1760111230882&q=DJ+Nights&sa=X&ved=2ahUKEwj-rLel_ZmQAxXyoWMGHQ3uL8AQxccNegQIGhAB&mstk=AUtExfDIbV4Fe1MYeQrW0BuOOPnKURAlNyx7tVEFwirVBA8awINniwPAvLrHpyqlXhU9m-m4hdyqErlikLMipg_c_OypWLm4ecslnhUS3I5uUQHy_trkmoVnGtHJi_6P5J2YBxRDn_XUrMh_2ug2QnsppGHZ67eAQ_nvnWwGlbsfhtW33zVDEiAXu50fhoAIFDG7NHf5381PIzYCQaLO1aQRZEfD_9XT8LyjDPHnI6cm-d1m8t76lr4CnQ9u6jvQdCBsYxZY1o6qDnR0Pq9KYFGnF1wB&csui=3"
          target="_blank"
          rel="noopener noreferrer"
          ><span class="text-wrapper-2">DJ Nights<br /></span
        ></a>
        <span class="span"><br /><br />*</span>
        <a
          href="https://www.google.com/search?sca_esv=69afb27cda6b1637&rlz=1C1GCEA_en-GB&cs=0&sxsrf=AE3TifOpY1-XUZJ6mZYSH_y2c1LRCiMpdA%3A1760111230882&q=Live+Music+Venues&sa=X&ved=2ahUKEwj-rLel_ZmQAxXyoWMGHQ3uL8AQxccNegQILBAB&mstk=AUtExfDIbV4Fe1MYeQrW0BuOOPnKURAlNyx7tVEFwirVBA8awINniwPAvLrHpyqlXhU9m-m4hdyqErlikLMipg_c_OypWLm4ecslnhUS3I5uUQHy_trkmoVnGtHJi_6P5J2YBxRDn_XUrMh_2ug2QnsppGHZ67eAQ_nvnWwGlbsfhtW33zVDEiAXu50fhoAIFDG7NHf5381PIzYCQaLO1aQRZEfD_9XT8LyjDPHnI6cm-d1m8t76lr4CnQ9u6jvQdCBsYxZY1o6qDnR0Pq9KYFGnF1wB&csui=3"
          target="_blank"
          rel="noopener noreferrer"
          ><span class="text-wrapper-2">Live Music Venues<br /></span
        ></a>
        <span class="span"><br /><br />*</span>
        <a
          href="https://www.google.com/search?sca_esv=69afb27cda6b1637&rlz=1C1GCEA_en-GB&cs=0&sxsrf=AE3TifOpY1-XUZJ6mZYSH_y2c1LRCiMpdA%3A1760111230882&q=Open-Air+Movies&sa=X&ved=2ahUKEwj-rLel_ZmQAxXyoWMGHQ3uL8AQxccNegQIRhAB&mstk=AUtExfDIbV4Fe1MYeQrW0BuOOPnKURAlNyx7tVEFwirVBA8awINniwPAvLrHpyqlXhU9m-m4hdyqErlikLMipg_c_OypWLm4ecslnhUS3I5uUQHy_trkmoVnGtHJi_6P5J2YBxRDn_XUrMh_2ug2QnsppGHZ67eAQ_nvnWwGlbsfhtW33zVDEiAXu50fhoAIFDG7NHf5381PIzYCQaLO1aQRZEfD_9XT8LyjDPHnI6cm-d1m8t76lr4CnQ9u6jvQdCBsYxZY1o6qDnR0Pq9KYFGnF1wB&csui=3"
          target="_blank"
          rel="noopener noreferrer"
          ><span class="text-wrapper-2">Open-Air Movies<br /></span
        ></a>
        <span class="span"><br /><br />*</span>
        <a
          href="https://www.google.com/search?sca_esv=69afb27cda6b1637&rlz=1C1GCEA_en-GB&cs=0&sxsrf=AE3TifOpY1-XUZJ6mZYSH_y2c1LRCiMpdA%3A1760111230882&q=Stand-up+Comedy&sa=X&ved=2ahUKEwj-rLel_ZmQAxXyoWMGHQ3uL8AQxccNegQIaxAB&mstk=AUtExfDIbV4Fe1MYeQrW0BuOOPnKURAlNyx7tVEFwirVBA8awINniwPAvLrHpyqlXhU9m-m4hdyqErlikLMipg_c_OypWLm4ecslnhUS3I5uUQHy_trkmoVnGtHJi_6P5J2YBxRDn_XUrMh_2ug2QnsppGHZ67eAQ_nvnWwGlbsfhtW33zVDEiAXu50fhoAIFDG7NHf5381PIzYCQaLO1aQRZEfD_9XT8LyjDPHnI6cm-d1m8t76lr4CnQ9u6jvQdCBsYxZY1o6qDnR0Pq9KYFGnF1wB&csui=3"
          target="_blank"
          rel="noopener noreferrer"
          ><span class="text-wrapper-2">Stand-up Comedy<br /></span
        ></a>
        <span class="span"><br /><br />*</span>
        <a
          href="https://www.google.com/search?sca_esv=69afb27cda6b1637&rlz=1C1GCEA_en-GB&cs=0&sxsrf=AE3TifOpY1-XUZJ6mZYSH_y2c1LRCiMpdA%3A1760111230882&q=Rooftop+Bars&sa=X&ved=2ahUKEwj-rLel_ZmQAxXyoWMGHQ3uL8AQxccNegQINBAB&mstk=AUtExfDIbV4Fe1MYeQrW0BuOOPnKURAlNyx7tVEFwirVBA8awINniwPAvLrHpyqlXhU9m-m4hdyqErlikLMipg_c_OypWLm4ecslnhUS3I5uUQHy_trkmoVnGtHJi_6P5J2YBxRDn_XUrMh_2ug2QnsppGHZ67eAQ_nvnWwGlbsfhtW33zVDEiAXu50fhoAIFDG7NHf5381PIzYCQaLO1aQRZEfD_9XT8LyjDPHnI6cm-d1m8t76lr4CnQ9u6jvQdCBsYxZY1o6qDnR0Pq9KYFGnF1wB&csui=3"
          target="_blank"
          rel="noopener noreferrer"
          ><span class="text-wrapper-2">Rooftop Bars</span></a
        >
      </p>
      <img class="sec" src="img/sec-logo1-1.png" />
    </div>
  </body>
</html>

globals.css

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

.android-large {
  background-color: #ffffff;
  width: 100%;
  min-width: 360px;
  min-height: 800px;
  position: relative;
}

.android-large .nebula {
  position: absolute;
  top: 0;
  left: 0;
  width: 360px;
  height: 800px;
  aspect-ratio: 0.58;
  object-fit: cover;
}

.android-large .text-wrapper {
  position: absolute;
  top: 57px;
  left: 14px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #ffd5d5;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-large .DJ-nights-live-music {
  position: absolute;
  top: 158px;
  left: 61px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.android-large .span {
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
}

.android-large .text-wrapper-2 {
  text-decoration: underline;
}

.android-large .sec {
  position: absolute;
  top: 213px;
  left: 34px;
  width: 290px;
  height: 284px;
  aspect-ratio: 1.02;
  object-fit: cover;
}

Page 3:

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
    <div class="android-large">
      <img class="neb" src="img/neb4-1.png" />
      <div class="text-wrapper">admission form</div>
      <div class="rectangle"></div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="text-wrapper-2">REGISTER</div>
      <div class="text-wrapper-3">NAME</div>
      <div class="text-wrapper-4">AGE</div>
      <div class="text-wrapper-5">REGISTER NUMBER</div>
      <div class="text-wrapper-6">DEPARTMENT</div>
      <div class="text-wrapper-7">MOBILE NUMBER</div>
    </div>
  </body>
</html>

globals.css

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

.android-large {
  background-color: #ffffff;
  width: 100%;
  min-width: 360px;
  min-height: 800px;
  position: relative;
}

.android-large .neb {
  position: absolute;
  top: 0;
  left: 0;
  width: 360px;
  height: 800px;
  aspect-ratio: 0.49;
  object-fit: cover;
}

.android-large .text-wrapper {
  position: absolute;
  top: 24px;
  left: 78px;
  width: 204px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #ffd7ed;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.android-large .rectangle {
  position: absolute;
  top: 136px;
  left: 34px;
  width: 264px;
  height: 26px;
  background-color: #d9d9d9;
}

.android-large .div {
  position: absolute;
  top: 208px;
  left: 34px;
  width: 92px;
  height: 32px;
  background-color: #d9d9d9;
}

.android-large .rectangle-2 {
  position: absolute;
  top: 286px;
  left: 34px;
  width: 241px;
  height: 35px;
  background-color: #d9d9d9;
}

.android-large .rectangle-3 {
  position: absolute;
  top: 351px;
  left: 34px;
  width: 236px;
  height: 38px;
  background-color: #d9d9d9;
}

.android-large .rectangle-4 {
  position: absolute;
  top: 444px;
  left: 34px;
  width: 241px;
  height: 33px;
  background-color: #d9d9d9;
}

.android-large .rectangle-5 {
  position: absolute;
  top: 632px;
  left: 52px;
  width: 246px;
  height: 66px;
  background-color: #fff600;
}

.android-large .text-wrapper-2 {
  position: absolute;
  top: 650px;
  left: 115px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #f90909;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.android-large .text-wrapper-3 {
  position: absolute;
  top: 139px;
  left: 43px;
  width: 292px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #8651c8;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.android-large .text-wrapper-4 {
  position: absolute;
  top: 209px;
  left: 34px;
  width: 132px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #975cb1;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.android-large .text-wrapper-5 {
  position: absolute;
  top: 288px;
  left: 42px;
  width: 307px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #9942af;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.android-large .text-wrapper-6 {
  position: absolute;
  top: 354px;
  left: 43px;
  width: 298px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #a45db0;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.android-large .text-wrapper-7 {
  position: absolute;
  top: 447px;
  left: 37px;
  width: 298px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #a75aa8;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}
# OUTPUT:<img width="646" height="426" alt="image" src="https://github.com/user-attachments/assets/88542148-6996-4abd-926a-e488d41dbf2e" />

# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
