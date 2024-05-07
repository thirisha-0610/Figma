# Ex09 Event Registration Web Application
## Date: 26/04/2024

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

HOME
```
<div style="width: 100%; height: 100%; position: relative; background: white">
    <div style="width: 360px; height: 92px; left: 0px; top: 0px; position: absolute; background: rgba(0, 162, 227, 0.75)"></div>
    <div style="width: 325px; height: 30px; left: 18px; top: 37px; position: absolute; text-align: center; color: black; font-size: 18px; font-family: Inter; font-weight: 800; word-wrap: break-word">SAVEETHA ENGINEERING COLLEGE</div>
    <div style="width: 360px; height: 0px; left: 0px; top: 94px; position: absolute; border: 5px #E3EE26 solid"></div>
    <img style="width: 229px; height: 229px; left: 66px; top: 122px; position: absolute" src="https://via.placeholder.com/229x229" />
    <div style="width: 304px; height: 104px; left: 29px; top: 366px; position: absolute; text-align: center; color: black; font-size: 20px; font-family: Inter; font-weight: 600; word-wrap: break-word">Affliated to Anna University<br/><br/>NIRF Ranked<br/>Autonomous Institution</div>
    <div style="width: 129px; height: 42px; left: 116px; top: 500px; position: absolute; background: #00A2E3; box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.50); border: 2px #E3EE26 solid"></div>
    <div style="width: 129px; height: 42px; left: 116px; top: 557px; position: absolute; background: #00A2E3; box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.50); border: 2px #E3EE26 solid"></div>
    <div style="width: 103px; height: 21px; left: 129px; top: 510px; position: absolute; text-align: center; color: white; font-size: 20px; font-family: Inter; font-weight: 800; word-wrap: break-word">LOGIN</div>
    <div style="width: 103px; height: 21px; left: 129px; top: 567px; position: absolute; text-align: center; color: white; font-size: 20px; font-family: Inter; font-weight: 800; word-wrap: break-word">REGISTER</div>
</div>
```
LOGIN
```
<div style="width: 100%; height: 100%; position: relative; background: white">
    <div style="width: 360px; height: 92px; left: 0px; top: 0px; position: absolute; background: rgba(0, 162, 227, 0.75)"></div>
    <div style="width: 360px; height: 0px; left: 0px; top: 94px; position: absolute; border: 5px #E3EE26 solid"></div>
    <div style="width: 325px; height: 30px; left: 17px; top: 39px; position: absolute; text-align: center; color: black; font-size: 18px; font-family: Inter; font-weight: 800; word-wrap: break-word">SAVEETHA ENGINEERING COLLEGE</div>
    <img style="width: 179px; height: 170px; left: 93px; top: 135px; position: absolute" src="https://via.placeholder.com/179x170" />
    <div style="width: 165px; height: 38px; left: 7px; top: 372px; position: absolute; text-align: center; color: black; font-size: 18px; font-family: Inter; font-weight: 600; word-wrap: break-word">USERNAME:</div>
    <div style="width: 165px; height: 38px; left: 7px; top: 440px; position: absolute; text-align: center; color: black; font-size: 18px; font-family: Inter; font-weight: 600; word-wrap: break-word">PASSWORD:</div>
    <div style="width: 170px; height: 41px; left: 160px; top: 361px; position: absolute; background: rgba(217, 217, 217, 0.35); box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25) inset"></div>
    <div style="width: 170px; height: 41px; left: 160px; top: 429px; position: absolute; background: rgba(217, 217, 217, 0.35); box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25) inset"></div>
    <div style="width: 129px; height: 42px; left: 116px; top: 502px; position: absolute; background: #00A2E3; box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.50); border: 2px #E3EE26 solid"></div>
    <div style="width: 103px; height: 21px; left: 129px; top: 512px; position: absolute; text-align: center; color: white; font-size: 20px; font-family: Inter; font-weight: 800; word-wrap: break-word">LOGIN</div>
</div>
```
REGISTER 1
```
<div style="width: 100%; height: 100%; position: relative; background: white">
    <div style="width: 360px; height: 92px; left: 0px; top: 0px; position: absolute; background: rgba(0, 162, 227, 0.75)"></div>
    <div style="width: 360px; height: 0px; left: 0px; top: 94px; position: absolute; border: 5px #E3EE26 solid"></div>
    <div style="width: 325px; height: 30px; left: 17px; top: 37px; position: absolute; text-align: center; color: black; font-size: 18px; font-family: Inter; font-weight: 800; word-wrap: break-word">SAVEETHA ENGINEERING COLLEGE</div>
    <div style="width: 360px; height: 640px; left: 400px; top: 1px; position: absolute; background: white"></div>
    <img style="width: 179px; height: 170px; left: 94px; top: 122px; position: absolute" src="https://via.placeholder.com/179x170" />
    <div style="width: 285px; height: 34px; left: 39px; top: 319px; position: absolute; text-align: center; color: black; font-size: 24px; font-family: Inter; font-weight: 800; word-wrap: break-word">REGISTERATION FORM</div>
    <div style="width: 96px; height: 26px; left: 52px; top: 380px; position: absolute; text-align: center"><span style="color: #FF0000; font-size: 10px; font-family: Inter; font-weight: 600; word-wrap: break-word">*</span><span style="color: black; font-size: 18px; font-family: Inter; font-weight: 600; word-wrap: break-word">NAME:</span></div>
    <div style="width: 139px; height: 29px; left: 9px; top: 506px; position: absolute; text-align: center"><span style="color: #FF0000; font-size: 10px; font-family: Inter; font-weight: 600; word-wrap: break-word">*</span><span style="color: black; font-size: 18px; font-family: Inter; font-weight: 600; word-wrap: break-word">USERNAME:</span></div>
    <div style="width: 120px; height: 30px; left: 19px; top: 443px; position: absolute; text-align: center"><span style="color: #FF0000; font-size: 10px; font-family: Inter; font-weight: 600; word-wrap: break-word">*</span><span style="color: black; font-size: 18px; font-family: Inter; font-weight: 600; word-wrap: break-word">PASSWORD:</span></div>
    <div style="width: 170px; height: 41px; left: 154px; top: 365px; position: absolute; background: rgba(217, 217, 217, 0.35); box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25) inset"></div>
    <div style="width: 170px; height: 41px; left: 154px; top: 432px; position: absolute; background: rgba(217, 217, 217, 0.35); box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25) inset"></div>
    <div style="width: 170px; height: 41px; left: 154px; top: 494px; position: absolute; background: rgba(217, 217, 217, 0.35); box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25) inset"></div>
    <div style="width: 21px; height: 21px; left: 133px; top: 574px; position: absolute; background: black; border-radius: 9999px"></div>
    <div style="width: 21px; height: 21px; left: 161px; top: 574px; position: absolute; background: #D9D9D9; border-radius: 9999px"></div>
    <div style="width: 21px; height: 21px; left: 189px; top: 574px; position: absolute; background: #D9D9D9; border-radius: 9999px"></div>
    <div style="width: 21px; height: 21px; left: 215px; top: 574px; position: absolute; background: #D9D9D9; border-radius: 9999px"></div>
</div>
```
REGISTER 2
```
<div style="width: 100%; height: 100%; position: relative; background: white">
    <div style="width: 360px; height: 92px; left: 0px; top: 0px; position: absolute; background: rgba(0, 162, 227, 0.75)"></div>
    <div style="width: 360px; height: 0px; left: 0px; top: 94px; position: absolute; border: 5px #E3EE26 solid"></div>
    <div style="width: 325px; height: 30px; left: 17px; top: 37px; position: absolute; text-align: center; color: black; font-size: 18px; font-family: Inter; font-weight: 800; word-wrap: break-word">SAVEETHA ENGINEERING COLLEGE</div>
    <div style="width: 156px; height: 37px; left: 11px; top: 157px; position: absolute; text-align: center"><span style="color: #FF0000; font-size: 10px; font-family: Inter; font-weight: 600; word-wrap: break-word">*</span><span style="color: black; font-size: 18px; font-family: Inter; font-weight: 600; word-wrap: break-word">COLLEGE NAME:</span></div>
    <div style="width: 139px; height: 29px; left: 23px; top: 283px; position: absolute; text-align: center"><span style="color: #FF0000; font-size: 10px; font-family: Inter; font-weight: 600; word-wrap: break-word">*</span><span style="color: black; font-size: 18px; font-family: Inter; font-weight: 600; word-wrap: break-word">AGE:</span></div>
    <div style="width: 146px; height: 26px; left: 16px; top: 353px; position: absolute; text-align: center"><span style="color: #FF0000; font-size: 10px; font-family: Inter; font-weight: 600; word-wrap: break-word">*</span><span style="color: black; font-size: 18px; font-family: Inter; font-weight: 600; word-wrap: break-word">DEPARTMENT:</span></div>
    <div style="width: 139px; height: 29px; left: 23px; top: 479px; position: absolute; text-align: center"><span style="color: #FF0000; font-size: 10px; font-family: Inter; font-weight: 600; word-wrap: break-word">*</span><span style="color: black; font-size: 18px; font-family: Inter; font-weight: 600; word-wrap: break-word">ROLL NUMBER:</span></div>
    <div style="width: 120px; height: 30px; left: 33px; top: 416px; position: absolute; text-align: center"><span style="color: #FF0000; font-size: 10px; font-family: Inter; font-weight: 600; word-wrap: break-word">*</span><span style="color: black; font-size: 18px; font-family: Inter; font-weight: 600; word-wrap: break-word">YEAR:</span></div>
    <div style="width: 170px; height: 41px; left: 168px; top: 338px; position: absolute; background: rgba(217, 217, 217, 0.35); box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25) inset"></div>
    <div style="width: 170px; height: 41px; left: 168px; top: 405px; position: absolute; background: rgba(217, 217, 217, 0.35); box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25) inset"></div>
    <div style="width: 170px; height: 41px; left: 168px; top: 467px; position: absolute; background: rgba(217, 217, 217, 0.35); box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25) inset"></div>
    <div style="width: 120px; height: 30px; left: 33px; top: 220px; position: absolute; text-align: center"><span style="color: #FF0000; font-size: 10px; font-family: Inter; font-weight: 600; word-wrap: break-word">*</span><span style="color: black; font-size: 18px; font-family: Inter; font-weight: 600; word-wrap: break-word">GENDER:</span></div>
    <div style="width: 170px; height: 41px; left: 168px; top: 142px; position: absolute; background: rgba(217, 217, 217, 0.35); box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25) inset"></div>
    <div style="width: 170px; height: 41px; left: 168px; top: 209px; position: absolute; background: rgba(217, 217, 217, 0.35); box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25) inset"></div>
    <div style="width: 170px; height: 41px; left: 168px; top: 271px; position: absolute; background: rgba(217, 217, 217, 0.35); box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25) inset"></div>
    <div style="width: 21px; height: 21px; left: 137px; top: 570px; position: absolute; background: #D9D9D9; border-radius: 9999px"></div>
    <div style="width: 21px; height: 21px; left: 165px; top: 570px; position: absolute; background: black; border-radius: 9999px"></div>
    <div style="width: 21px; height: 21px; left: 193px; top: 570px; position: absolute; background: #D9D9D9; border-radius: 9999px"></div>
    <div style="width: 21px; height: 21px; left: 221px; top: 570px; position: absolute; background: #D9D9D9; border-radius: 9999px"></div>
</div>
```
REGISTER 3
```
<div style="width: 100%; height: 100%; position: relative; background: white">
    <div style="width: 360px; height: 92px; left: 0px; top: 0px; position: absolute; background: rgba(0, 162, 227, 0.75)"></div>
    <div style="width: 360px; height: 0px; left: 0px; top: 94px; position: absolute; border: 5px #E3EE26 solid"></div>
    <div style="width: 325px; height: 30px; left: 17px; top: 37px; position: absolute; text-align: center; color: black; font-size: 18px; font-family: Inter; font-weight: 800; word-wrap: break-word">SAVEETHA ENGINEERING COLLEGE</div>
    <div style="width: 156px; height: 37px; left: 5px; top: 141px; position: absolute; text-align: center"><span style="color: #FF0707; font-size: 10px; font-family: Inter; font-weight: 400; word-wrap: break-word">*</span><span style="color: black; font-size: 18px; font-family: Inter; font-weight: 600; word-wrap: break-word">EMAIL-ID:</span></div>
    <div style="width: 146px; height: 26px; left: 10px; top: 380px; position: absolute; text-align: center"><span style="color: #FF0000; font-size: 10px; font-family: Inter; font-weight: 400; word-wrap: break-word">*</span><span style="color: black; font-size: 18px; font-family: Inter; font-weight: 600; word-wrap: break-word">EVENT1:</span></div>
    <div style="width: 120px; height: 30px; left: 27px; top: 443px; position: absolute; text-align: center; color: black; font-size: 18px; font-family: Inter; font-weight: 600; word-wrap: break-word">EVENT2:</div>
    <div style="width: 120px; height: 30px; left: 24px; top: 504px; position: absolute; text-align: center"><span style="color: #FF0000; font-size: 10px; font-family: Inter; font-weight: 400; word-wrap: break-word">*</span><span style="color: black; font-size: 18px; font-family: Inter; font-weight: 600; word-wrap: break-word">PHOTO</span></div>
    <div style="width: 170px; height: 41px; left: 162px; top: 365px; position: absolute; background: rgba(217, 217, 217, 0.35); box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25) inset"></div>
    <div style="width: 170px; height: 41px; left: 162px; top: 432px; position: absolute; background: rgba(217, 217, 217, 0.35); box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25) inset"></div>
    <div style="width: 170px; height: 41px; left: 161px; top: 491px; position: absolute; background: rgba(217, 217, 217, 0.35); box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25) inset"></div>
    <div style="width: 170px; height: 41px; left: 162px; top: 126px; position: absolute; background: rgba(217, 217, 217, 0.35); box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25) inset"></div>
    <div style="width: 315px; left: 17px; top: 317px; position: absolute; text-align: center"><span style="color: #FF0606; font-size: 12px; font-family: Inter; font-weight: 300; word-wrap: break-word"><br/></span><span style="color: #FF0000; font-size: 12px; font-family: Inter; font-weight: 300; word-wrap: break-word">*</span><span style="color: black; font-size: 12px; font-family: Inter; font-weight: 300; word-wrap: break-word">Each student can attend a maximum of only 2 events</span></div>
    <div style="width: 103px; left: 177px; top: 489px; position: absolute; text-align: center; color: black; font-size: 12px; font-family: Inter; font-weight: 300; word-wrap: break-word"><br/>CHOOSE FILE</div>
    <div style="width: 285px; height: 34px; left: 37px; top: 282px; position: absolute; text-align: center; color: black; font-size: 24px; font-family: Inter; font-weight: 800; word-wrap: break-word">EVENTS</div>
    <div style="width: 139px; height: 29px; left: 17px; top: 208px; position: absolute; text-align: center"><span style="color: #F90909; font-size: 10px; font-family: Inter; font-weight: 400; word-wrap: break-word">*</span><span style="color: black; font-size: 18px; font-family: Inter; font-weight: 600; word-wrap: break-word">CELL NUMBER:</span></div>
    <div style="width: 170px; height: 41px; left: 162px; top: 196px; position: absolute; background: rgba(217, 217, 217, 0.35); box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25) inset"></div>
    <div style="width: 21px; height: 21px; left: 165px; top: 569px; position: absolute; background: #D9D9D9; border-radius: 9999px"></div>
    <div style="width: 21px; height: 21px; left: 135px; top: 569px; position: absolute; background: #D9D9D9; border-radius: 9999px"></div>
    <div style="width: 21px; height: 21px; left: 194px; top: 569px; position: absolute; background: black; border-radius: 9999px"></div>
    <div style="width: 21px; height: 21px; left: 222px; top: 569px; position: absolute; background: #D9D9D9; border-radius: 9999px"></div>
</div>
```
PREVIEW
```
<div style="width: 100%; height: 100%; position: relative; background: white">
    <div style="width: 360px; height: 92px; left: 0px; top: 0px; position: absolute; background: rgba(0, 162, 227, 0.75)"></div>
    <div style="width: 360px; height: 0px; left: 0px; top: 94px; position: absolute; border: 5px #E3EE26 solid"></div>
    <div style="width: 325px; height: 30px; left: 17px; top: 37px; position: absolute; text-align: center; color: black; font-size: 18px; font-family: Inter; font-weight: 800; word-wrap: break-word">SAVEETHA ENGINEERING COLLEGE</div>
    <img style="width: 232px; height: 230px; left: 64px; top: 151px; position: absolute; border-radius: 9999px; border: 6px #E3EE26 solid" src="https://via.placeholder.com/232x230" />
    <div style="width: 285px; height: 34px; left: 37px; top: 106px; position: absolute; text-align: center; color: black; font-size: 26px; font-family: Inter; font-weight: 800; word-wrap: break-word">PREVIEW</div>
    <div style="width: 207px; height: 153px; left: 80px; top: 403px; position: absolute; text-align: center; color: black; font-size: 18px; font-family: Inter; font-weight: 600; word-wrap: break-word">NAME: xxxx<br/>GENDER: xxxx<br/>YEAR: xxxx<br/>DEPARTMENT: xxxx<br/>EMAIL-ID: xxxx<br/>CELL NUMBER: xxxx<br/></div>
    <div style="width: 129px; height: 42px; left: 115px; top: 557px; position: absolute; background: #00A2E3; box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.50); border: 2px #E3EE26 solid"></div>
    <div style="width: 103px; height: 21px; left: 128px; top: 567px; position: absolute; text-align: center; color: white; font-size: 20px; font-family: Inter; font-weight: 800; word-wrap: break-word">REGISTER</div>
</div>
```
THANK YOU
```
<div style="width: 100%; height: 100%; position: relative; background: white">
    <div style="width: 360px; height: 92px; left: 0px; top: 0px; position: absolute; background: rgba(0, 162, 227, 0.75)"></div>
    <div style="width: 360px; height: 151px; left: 0px; top: 489px; position: absolute; background: rgba(0, 162, 227, 0.75)"></div>
    <div style="width: 360px; height: 0px; left: 0px; top: 94px; position: absolute; border: 5px #E3EE26 solid"></div>
    <div style="width: 360px; height: 0px; left: 0px; top: 488px; position: absolute; border: 5px #E3EE26 solid"></div>
    <div style="width: 325px; height: 30px; left: 17px; top: 37px; position: absolute; text-align: center; color: black; font-size: 18px; font-family: Inter; font-weight: 800; word-wrap: break-word">SAVEETHA ENGINEERING COLLEGE</div>
    <div style="width: 285px; height: 34px; left: 37px; top: 191px; position: absolute; text-align: center; color: black; font-size: 36px; font-family: Inter; font-weight: 800; word-wrap: break-word">THANK YOU</div>
    <div style="width: 262px; height: 78px; left: 54px; top: 258px; position: absolute; text-align: center; color: black; font-size: 20px; font-family: Inter; font-weight: 600; word-wrap: break-word">We are all eagerly waiting for your participation in the with us</div>
    <div style="width: 129px; height: 42px; left: 115px; top: 358px; position: absolute; background: #00A2E3; box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.50); border: 2px #E3EE26 solid"></div>
    <div style="width: 116px; height: 22px; left: 122px; top: 368px; position: absolute; text-align: center; color: white; font-size: 20px; font-family: Inter; font-weight: 800; word-wrap: break-word">BROCHURE</div>
    <div style="width: 71px; height: 21px; left: 144px; top: 534px; position: absolute; text-align: center; color: white; font-size: 15px; font-family: Inter; font-weight: 600; word-wrap: break-word">E-mail</div>
    <div style="width: 71px; height: 21px; left: 146px; top: 578px; position: absolute; text-align: center; color: white; font-size: 15px; font-family: Inter; font-weight: 600; word-wrap: break-word">Phone</div>
    <div style="width: 325px; height: 16px; left: 23px; top: 556px; position: absolute; text-align: center; color: white; font-size: 13px; font-family: Inter; font-weight: 400; word-wrap: break-word">saveethaengineeringcollege@gmail.com</div>
    <div style="width: 325px; height: 16px; left: 17px; top: 599px; position: absolute; text-align: center; color: white; font-size: 13px; font-family: Inter; font-weight: 400; word-wrap: break-word">7558124630</div>
    <div style="width: 325px; height: 16px; left: 18px; top: 617px; position: absolute; text-align: center; color: white; font-size: 13px; font-family: Inter; font-weight: 400; word-wrap: break-word">7558124780</div>
    <div style="width: 136px; height: 26px; left: 112px; top: 500px; position: absolute; text-align: center; color: white; font-size: 20px; font-family: Inter; font-weight: 800; word-wrap: break-word">CONTACT US</div>
</div>
```

## OUTPUT:
![Screenshot 2024-05-07 161551](https://github.com/thirisha-0610/Figma/assets/149347494/810afa0f-a4a6-4a59-a7ee-4f7e38c070b9)

![Screenshot 2024-05-07 161620](https://github.com/thirisha-0610/Figma/assets/149347494/77f8cbbe-35e5-4afe-b13e-512d6ad0a8f9)

![Screenshot 2024-05-07 161639](https://github.com/thirisha-0610/Figma/assets/149347494/298de56f-7b16-44fe-8d30-f468884d23ca)

![Screenshot 2024-05-07 161705](https://github.com/thirisha-0610/Figma/assets/149347494/96b9c60a-0272-41bc-aca8-60f4a9550846)

![Screenshot 2024-05-07 161743](https://github.com/thirisha-0610/Figma/assets/149347494/051abb6e-30c8-48e4-b32b-f5c2d34b714f)

![Screenshot 2024-05-07 161803](https://github.com/thirisha-0610/Figma/assets/149347494/e9e67584-d4b1-4799-b7c8-6c8ea1cb700d)

![Screenshot 2024-05-07 161825](https://github.com/thirisha-0610/Figma/assets/149347494/953244e8-531e-4934-83b9-24d65cb76306)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
