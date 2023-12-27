# Ex09 Event Registration Web Application
## Date:27.12.23

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
home page
<div style="width: 100%; height: 100%; position: relative; background-image: url(https://via.placeholder.com/360x640)">
<img style="width: 360px; height: 86px; left: 0px; top: 0px; position: absolute" src="https://via.placeholder.com/360x86" />
<img style="width: 102px; height: 114px; left: 130px; top: 93px; position: absolute" src="https://via.placeholder.com/102x114" />
<div style="width: 211px; height: 31px; left: 85px; top: 270px; position: absolute; background: #5E80D6"></div>
<div style="width: 100px; height: 100px; left: 76px; top: 277px; position: absolute"></div>
<div style="width: 211px; height: 30px; left: 85px; top: 311px; position: absolute; background: #5E80D6"></div>
<div style="left: 113px; top: 317px; position: absolute; text-align: center; color: white; font-size: 12px; font-family: Almarai; font-weight: 700; word-wrap: break-word"> LOGIN</div>
<div style="left: 123px; top: 233px; position: absolute; text-align: center; color: white; font-size: 24px; font-family: Inter; font-weight: 700; word-wrap: break-word">VOICIFY AI</div>
<div style="width: 170px; left: 95px; top: 277px; position: absolute; text-align: center; color: white; font-size: 16px; font-family: Aleo; font-weight: 700; word-wrap: break-word">REGISTER</div>
</div>
// LOGIN
color: white;
font-size: 12px;
font-family: Almarai;
font-weight: 700;
word-wrap: break-word
---
// VOICIFY AI
color: white;
font-size: 24px;
font-family: Inter;
font-weight: 700;
word-wrap: break-word
---
// REGISTER
color: white;
font-size: 16px;
font-family: Aleo;
font-weight: 700;
word-wrap: break-word

page1

<div style="width: 100%; height: 100%; position: relative; background-image: url(https://via.placeholder.com/360x640); flex-direction: column; justify-content: flex-start; align-items: flex-start; display: inline-flex">
<div style="width: 504px; text-align: center; color: white; font-size: 40px; font-family: Coda Caption; font-weight: 800; word-wrap: break-word">AI WORKSHOP</div>
<div style="width: 513px; height: 52px; text-align: center; color: white; font-size: 16px; font-family: Comfortaa; font-weight: 700; word-wrap: break-word">ROADMAP TO WEB DEVELOPMENT</div>
<div style="width: 571px; height: 29px; text-align: center; color: white; font-size: 16px; font-family: Comfortaa; font-weight: 700; word-wrap: break-word">WORKSHOP ON DATA ANALYTICS</div>
<div style="width: 798px; height: 30px; text-align: center; color: white; font-size: 16px; font-family: Comfortaa; font-weight: 700; word-wrap: break-word"> DATA STRUCTURE AND ALGORITHMS</div>
</div>
// AI WORKSHOP
color: white;
font-size: 40px;
font-family: Coda Caption;
font-weight: 800;
word-wrap: break-word
---
// ROADMAP TO WEB DEVELOPMENT
color: white;
font-size: 16px;
font-family: Comfortaa;
font-weight: 700;
word-wrap: break-word
---
// WORKSHOP ON DATA ANALYTICS
color: white;
font-size: 16px;
font-family: Comfortaa;
font-weight: 700;
word-wrap: break-word
---
// DATA STRUCTURE AND ALGORITHMS
color: white;
font-size: 16px;
font-family: Comfortaa;
font-weight: 700;
word-wrap: break-word

page2

<div style="width: 100%; height: 100%; position: relative; background-image: url(https://via.placeholder.com/360x640)">
<div style="width: 644px; height: 46px; left: -140px; top: 14px; position: absolute; text-align: center; color: white; font-size: 32px; font-family: Inter; font-weight: 400; word-wrap: break-word">event registration form</div>
<div style="left: 20px; top: 95px; position: absolute; text-align: center; color: white; font-size: 20px; font-family: Inter; font-weight: 700; word-wrap: break-word">Name:</div>
<div style="width: 188px; left: -23px; top: 130px; position: absolute; text-align: center; color: white; font-size: 20px; font-family: Inter; font-weight: 700; word-wrap: break-word">Mobile no:</div>
<div style="width: 410px; height: 31px; left: -50px; top: 165px; position: absolute; text-align: center; color: white; font-size: 20px; font-family: Inter; font-weight: 700; word-wrap: break-word">you are interested in:</div>
<div style="width: 611px; height: 26px; left: -107px; top: 211px; position: absolute; text-align: center; color: white; font-size: 16px; font-family: Comfortaa; font-weight: 700; word-wrap: break-word">ROADMAP TO WEB DEVELOPMENT</div>
<div style="width: 181px; height: 91px; left: -148px; top: 125px; position: absolute"></div>
<div style="width: 15px; height: 12px; left: 17px; top: 213px; position: absolute; background: #D9D9D9"></div>
<div style="width: 357px; height: 31px; left: 15px; top: 247px; position: absolute; text-align: center; color: white; font-size: 16px; font-family: Comfortaa; font-weight: 700; word-wrap: break-word">WORKSHOP ON DATA ANALYTICS</div>
<div style="width: 321px; height: 31px; left: 33px; top: 278px; position: absolute; text-align: center; color: white; font-size: 16px; font-family: Comfortaa; font-weight: 700; word-wrap: break-word"> DATA STRUCTURE AND ALGORITHMS</div>
<div style="width: 15px; height: 12px; left: 17px; top: 250px; position: absolute; background: #D9D9D9"></div>
<div style="width: 15px; height: 12px; left: 17px; top: 280px; position: absolute; background: #D9D9D9"></div>
</div>

// event registration form
color: white;
font-size: 32px;
font-family: Inter;
font-weight: 400;
word-wrap: break-word
---
// Name:
color: white;
font-size: 20px;
font-family: Inter;
font-weight: 700;
word-wrap: break-word
---
// Mobile no:
color: white;
font-size: 20px;
font-family: Inter;
font-weight: 700;
word-wrap: break-word
---
// you are interested in:
color: white;
font-size: 20px;
font-family: Inter;
font-weight: 700;
word-wrap: break-word
---
// ROADMAP TO WEB DEVELOPMENT
color: white;
font-size: 16px;
font-family: Comfortaa;
font-weight: 700;
word-wrap: break-word
---
// WORKSHOP ON DATA ANALYTICS
color: white;
font-size: 16px;
font-family: Comfortaa;
font-weight: 700;
word-wrap: break-word
---
// DATA STRUCTURE AND ALGORITHMS
color: white;
font-size: 16px;
font-family: Comfortaa;
font-weight: 700;
word-wrap: break-word

 page3

 <div style="width: 100%; height: 100%; position: relative; background-image: url(https://via.placeholder.com/360x640)">
<div style="width: 484px; left: -67px; top: 70px; position: absolute; text-align: center; color: white; font-size: 40px; font-family: Courier Prime; font-weight: 700; word-wrap: break-word">THANK YOU</div>
<div style="width: 613px; left: -126px; top: 177px; position: absolute; text-align: center; color: white; font-size: 16px; font-family: Courier Prime; font-weight: 700; word-wrap: break-word">“predicting the future isn’t magic,</div>
<div style="width: 579px; left: -105px; top: 215px; position: absolute; text-align: center; color: white; font-size: 16px; font-family: Courier Prime; font-weight: 700; word-wrap: break-word">it’s artifical intelligence.”</div>
</div>

// THANK YOU
color: white;
font-size: 40px;
font-family: Courier Prime;
font-weight: 700;
word-wrap: break-word
---
// “predicting the future isn’t magic,
color: white;
font-size: 16px;
font-family: Courier Prime;
font-weight: 700;
word-wrap: break-word
---
// it’s artifical intelligence.”
color: white;
font-size: 16px;
font-family: Courier Prime;
font-weight: 700;
word-wrap: break-word
```
## OUTPUT:
![Alt text](<Screenshot (36).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
