# Ex09 Event Registration Web Application
## Date:10-11-2025

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
HOME PAGE :

<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  <link href="https://fonts.googleapis.com/css?family=Poppins&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-se-1-1">
<div class="rectangle-1-2"></div>
<div class="node-3"></div>
<img src="images/node-4.png" class="node-4" alt="screenshot_2025-11-02_124857-removebg-preview" />
<img src="images/node-5.png" class="node-5" alt="screenshot_2025-11-02_133206-removebg-preview-1" />
<div class="rectangle-2-6"></div>
<p class="text-7"><span class="text-rgb-254-254-249">REGISTER</span></p>
</div>

</body>
</html>

style.css :
:root {
  --font-family-poppins: 'Poppins', sans-serif;
  --text-rgb-254-254-249: rgba(254, 254, 249, 1);
}

.text-rgb-254-254-249 {
  color: var(--text-rgb-254-254-249);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.rectangle-1-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(30, 30, 30, 1);
}

.node-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.node-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.node-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.rectangle-2-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(108, 88, 27, 1);
  border-radius: 50px;
}

.text-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-poppins);
  font-weight: 700;
  font-size: 40px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-254-254-249);
}

.iphone-se-1-1 {
@media (max-width: 1440px) {
  .iphone-se-1-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-se-1-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(0, 0, 0, 1);
  border: 2px solid rgba(251, 255, 253, 1);
}
```
```
EVENTS PAGE :

<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  <link href="https://fonts.googleapis.com/css?family=Poppins&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="android-compact-1-1">
<img src="images/node-2.png" class="node-2" alt="vibrant-music-festival-stockcake-1" />
<img src="images/node-3.png" class="node-3" alt="screenshot_2025-11-02_124857-removebg-preview" />
<p class="text-4"><span class="text-rgb-232-229-28">EVENTS</span></p>
<p class="text-5"><span class="text-black"> </span></p>
<p class="text-6"><span class="text-black">→TECH EVENTS</span></p>
<p class="text-7"><span class="text-black">→TECH QUEST</span></p>
<p class="text-8"><span class="text-black">→Cloud Escape Room</span></p>
<p class="text-9"><span class="text-black">→TECH SQUID</span></p>
<p class="text-10"><span class="text-black">→Data Analytics</span></p>
</div>

</body>
</html>

STYLE.CSS:

/* Add font files for Post No Bills Jaffna ExtraBold */
@font-face {
  font-family: 'Post No Bills Jaffna ExtraBold';
  src: url('fonts/post-no-bills-jaffna-extrabold.woff2') format('woff2'),
       url('fonts/post-no-bills-jaffna-extrabold.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-post-no-bills-jaffna-extrabold: 'Post No Bills Jaffna ExtraBold', sans-serif;
  --font-family-poppins: 'Poppins', sans-serif;
  --text-rgb-232-229-28: rgba(232, 229, 28, 1);
  --text-black: rgba(0, 0, 0, 1);
}

.text-rgb-232-229-28 {
  color: var(--text-rgb-232-229-28);
}

.text-black {
  color: var(--text-black);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.node-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.node-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.text-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-post-no-bills-jaffna-extrabold);
  font-weight: normal;
  font-size: 96px;
  letter-spacing: 1%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-232-229-28);
}

.text-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-poppins);
  font-weight: 700;
  font-size: 40px;
  letter-spacing: 1%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-poppins);
  font-weight: 700;
  font-size: 32px;
  letter-spacing: 1%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-poppins);
  font-weight: 700;
  font-size: 32px;
  letter-spacing: 1%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-poppins);
  font-weight: 700;
  font-size: 32px;
  letter-spacing: 1%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-9 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-poppins);
  font-weight: 700;
  font-size: 32px;
  letter-spacing: 1%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-10 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-poppins);
  font-weight: 700;
  font-size: 32px;
  letter-spacing: 1%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.android-compact-1-1 {
@media (max-width: 1440px) {
  .android-compact-1-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .android-compact-1-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
  border: 2px solid rgba(255, 247, 247, 1);
}
```
REGISTRATION PAGE :

<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  <link href="https://fonts.googleapis.com/css?family=Poppins&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="android-compact-2-1">
<p class="text-2"><span class="text-white">EVENT REGISTRATION </span></p>
<img src="images/line-2-4.svg" class="line-2-4" alt="line-2" />
<div class="rectangle-3-5"></div>
<div class="rectangle-5-6"></div>
<div class="rectangle-6-7"></div>
<div class="rectangle-7-8"></div>
<div class="rectangle-8-9"></div>
<div class="rectangle-9-10"></div>
<p class="text-11"><span class="text-white">Select Event    </span></p>
<p class="text-12"><span class="text-white">:</span></p>
<p class="text-13"><span class="text-white">Name  :</span></p>
<p class="text-14"><span class="text-white">Reg No :</span></p>
<p class="text-15"><span class="text-white">Dept     :</span></p>
<p class="text-16"><span class="text-white">Mobile :</span></p>
<p class="text-17"><span class="text-white">Email Id:</span></p>
<div class="rectangle-3-18"></div>
<p class="text-19"><span class="text-white">SUBMIT</span></p>
<img src="images/node-20.png" class="node-20" alt="screenshot_2025-11-02_124857-removebg-preview" />
</div>

</body>
</html>

STYLE.CSS:
:root {
  --font-family-poppins: 'Poppins', sans-serif;
  --text-white: rgba(255, 255, 255, 1);
}

.text-white {
  color: var(--text-white);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.text-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-poppins);
  font-weight: 700;
  font-size: 36px;
  letter-spacing: 1%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.line-1-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border: 0px solid rgba(255, 255, 255, 1);
  border: none;
  outline: none;
}

.line-2-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border: 1px solid rgba(255, 248, 248, 1);
  border: none;
  outline: none;
}

.rectangle-3-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: inset 0px 4px 4px 0px rgba(0,0,0,0.5);
  background-color: rgba(217, 217, 217, 1);
}

.rectangle-5-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: inset 0px 4px 4px 0px rgba(0,0,0,0.5);
  background-color: rgba(217, 217, 217, 1);
}

.rectangle-6-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: inset 0px 4px 4px 0px rgba(0,0,0,0.5);
  background-color: rgba(217, 217, 217, 1);
}

.rectangle-7-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: inset 0px 4px 4px 0px rgba(0,0,0,0.5);
  background-color: rgba(217, 217, 217, 1);
}

.rectangle-8-9 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: inset 0px 4px 4px 0px rgba(0,0,0,0.5);
  background-color: rgba(217, 217, 217, 1);
}

.rectangle-9-10 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: inset 0px 4px 4px 0px rgba(0,0,0,0.5);
  background-color: rgba(217, 217, 217, 1);
}

.text-11 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-poppins);
  font-weight: 500;
  font-size: 32px;
  letter-spacing: 1%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.text-12 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-poppins);
  font-weight: 500;
  font-size: 32px;
  letter-spacing: 1%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.text-13 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-poppins);
  font-weight: 500;
  font-size: 32px;
  letter-spacing: 1%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.text-14 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-poppins);
  font-weight: 500;
  font-size: 32px;
  letter-spacing: 1%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.text-15 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-poppins);
  font-weight: 500;
  font-size: 32px;
  letter-spacing: 1%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.text-16 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-poppins);
  font-weight: 500;
  font-size: 32px;
  letter-spacing: 1%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.text-17 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-poppins);
  font-weight: 500;
  font-size: 32px;
  letter-spacing: 1%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.rectangle-3-18 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(216, 83, 30, 1);
  border-radius: 50px;
}

.text-19 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-poppins);
  font-weight: normal;
  font-size: 32px;
  letter-spacing: 3%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.node-20 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.android-compact-2-1 {
@media (max-width: 1440px) {
  .android-compact-2-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .android-compact-2-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(0, 26, 77, 1);
  border: 1px solid rgba(248, 238, 238, 1);
}
```
CONTACT PAGE:

<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  <link href="https://fonts.googleapis.com/css?family=Poppins&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="android-compact-3-1">
<img src="images/node-2.png" class="node-2" alt="screenshot_2025-11-02_124857-removebg-preview-1" />
<p class="text-3"><span class="text-white">Thank You
        For 
Registering</span></p>
<p class="text-4"><span class="text-white">contact us :</span></p>
<p class="text-5"><span class="text-white">Email :</span></p>
<p class="text-6"><span class="text-white">saveethadrestein@gmail.com</span></p>
<p class="text-7"><span class="text-white">phone:</span></p>
<p class="text-8"><span class="text-white">+91xxxxxxxxxx</span></p>
</div>

</body>
</html>

STYLE.CSS:

/* Add font files for PoetsenOne */
@font-face {
  font-family: 'PoetsenOne';
  src: url('fonts/poetsenone.woff2') format('woff2'),
       url('fonts/poetsenone.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

/* Add font files for Port Lligat Sans */
@font-face {
  font-family: 'Port Lligat Sans';
  src: url('fonts/port-lligat-sans.woff2') format('woff2'),
       url('fonts/port-lligat-sans.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-poetsenone: 'PoetsenOne', sans-serif;
  --font-family-port-lligat-sans: 'Port Lligat Sans', sans-serif;
  --font-family-poppins: 'Poppins', sans-serif;
  --text-white: rgba(255, 255, 255, 1);
}

.text-white {
  color: var(--text-white);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.node-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.text-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  border: 1px solid rgba(68, 250, 159, 1);
  font-family: var(--font-family-poetsenone);
  font-weight: normal;
  font-size: 64px;
  letter-spacing: 2%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.text-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-port-lligat-sans);
  font-weight: normal;
  font-size: 40px;
  letter-spacing: 2%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.text-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-poppins);
  font-weight: normal;
  font-size: 32px;
  letter-spacing: 2%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.text-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-poppins);
  font-weight: normal;
  font-size: 24px;
  letter-spacing: 2%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.text-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-poppins);
  font-weight: normal;
  font-size: 32px;
  letter-spacing: 2%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.text-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-poppins);
  font-weight: normal;
  font-size: 32px;
  letter-spacing: 2%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.android-compact-3-1 {
@media (max-width: 1440px) {
  .android-compact-3-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .android-compact-3-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(37, 2, 19, 1);
  border: 1px solid rgba(255, 246, 246, 1);
}
```

## OUTPUT:
![alt text](<Screenshot 2025-11-10 215549.png>)

## PAGE 1:


![alt text](<iPhone SE - 1.jpg>)

## PAGE 2:

![alt text](<Android Compact - 1.jpg>)

## PAGE 3:

![alt text](<Android Compact - 2.jpg>)

## PAGE 4:

![alt text](<Android Compact - 3.jpg>)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
