# Ex09 Event Registration Web Application
## Date:13-11-2024

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
## Frame2:
```
<div style="width: 217px; height: 412px; position: relative; background: black">
  <img style="width: 217px; height: 412px; left: 0px; top: 0px; position: absolute; box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25); border: 1px black solid" src="https://via.placeholder.com/217x412" />
  <img style="width: 200px; height: 30.08px; left: 8px; top: 11px; position: absolute" src="https://via.placeholder.com/200x30" />
  <div style="width: 40px; height: 40px; left: 88px; top: 86px; position: absolute; background: #D9BDFE; border-radius: 100px; overflow: hidden">
    <div style="width: 28.18px; height: 25.63px; left: 5.91px; top: 10px; position: absolute; background: #523C72"></div>
  </div>
  <div style="width: 102px; height: 30px; left: 211px; top: 515px; position: absolute"></div>
  <div style="width: 103px; height: 34px; left: 56px; top: 143px; position: absolute; background: #0DEAFE; box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25) inset; border: 1px black solid"></div>
  <div style="left: 64px; top: 151px; position: absolute; color: black; font-size: 24px; font-family: Inter; font-weight: 500; word-wrap: break-word"><br/></div>
  <div style="left: 67px; top: 153px; position: absolute; color: black; font-size: 16px; font-family: Inter; font-weight: 500; word-wrap: break-word">    LOGIN</div>
  <div style="width: 103px; height: 32px; left: 56px; top: 188px; position: absolute; background: #06E6FF; box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25) inset; border: 1px black solid"></div>
  <div style="left: 69px; top: 196px; position: absolute; color: black; font-size: 16px; font-family: Inter; font-weight: 500; word-wrap: break-word">REGISTER<br/></div>
</div>
```
## Frame3:
```
<div style="width: 226px; height: 412px; position: relative; background: white">
  <img style="width: 226px; height: 412px; left: 0px; top: 0px; position: absolute" src="https://via.placeholder.com/226x412" />
  <div style="width: 80px; height: 160px; left: 80px; top: 107px; position: absolute; color: #E62323; font-size: 16px; font-family: Inria Serif; font-weight: 400; letter-spacing: 0.16px; word-wrap: break-word">Football<br/>Basketball<br/>Cricket<br/>Volleyball<br/>400MTS<br/>200MTS<br/>100 MTS<br/></div>
  <div style="width: 171px; height: 23px; left: 40px; top: 20px; position: absolute; color: black; font-size: 16px; font-family: Inter; font-weight: 500; word-wrap: break-word">SPORTS DAY EVENTS<br/></div>
  <div style="width: 135px; height: 36px; left: 57px; top: 20px; position: absolute"></div>
</div>
```
## Frame4:
```
<div style="width: 222px; height: 412px; position: relative; background: white">
  <img style="width: 222px; height: 412px; left: 0px; top: 0px; position: absolute" src="https://via.placeholder.com/222x412" />
  <div style="width: 130px; height: 28px; left: 26px; top: 262px; position: absolute; background: white"></div>
  <div style="width: 144px; height: 29px; left: 26px; top: 144px; position: absolute; background: white"></div>
  <div style="left: 45px; top: 267px; position: absolute; color: black; font-size: 14px; font-family: Itim; font-weight: 400; word-wrap: break-word">Mobile Number</div>
  <div style="width: 204px; height: 34px; left: 7px; top: 10px; position: absolute"><span style="color: #653333; font-size: 13px; font-family: Inter; font-weight: 700; word-wrap: break-word">EVENT REGISTRATION FORM<br/></span><span style="color: #EA1418; font-size: 12px; font-family: Inter; font-weight: 100; word-wrap: break-word">Fill the details</span></div>
  <div style="width: 144px; height: 27px; left: 26px; top: 68px; position: absolute; background: white"></div>
  <div style="left: 39px; top: 74px; position: absolute; color: black; font-size: 14px; font-family: Itim; font-weight: 400; word-wrap: break-word">Full Name</div>
  <div style="width: 144px; height: 27px; left: 26px; top: 106px; position: absolute; background: white"></div>
  <div style="left: 58px; top: 110px; position: absolute; color: black; font-size: 14px; font-family: Itim; font-weight: 400; word-wrap: break-word">Gender<br/></div>
  <div style="width: 167px; height: 27px; left: 26px; top: 184px; position: absolute; background: #F5F5F5"></div>
  <div style="width: 153px; height: 29px; left: 26px; top: 222px; position: absolute; background: white"></div>
  <div style="width: 137px; height: 27px; left: 26px; top: 301px; position: absolute; background: white"></div>
  <div style="width: 1px; height: 1px; left: 26px; top: 321px; position: absolute; background: #D9D9D9"></div>
  <div style="width: 113px; height: 28px; left: 80px; top: 373px; position: absolute; background: #FADC15; border: 1px black solid"></div>
  <div style="left: 101px; top: 378px; position: absolute; color: black; font-size: 14px; font-family: Itim; font-weight: 400; word-wrap: break-word">REGISTER<br/></div>
  <div style="left: 71px; top: 153px; position: absolute; color: black; font-size: 14px; font-family: Itim; font-weight: 400; word-wrap: break-word">Age</div>
  <div style="left: 53px; top: 189px; position: absolute; color: black; font-size: 14px; font-family: Itim; font-weight: 400; word-wrap: break-word">Register Number</div>
  <div style="left: 48px; top: 228px; position: absolute; color: black; font-size: 14px; font-family: Itim; font-weight: 400; word-wrap: break-word">Department</div>
  <div style="width: 108px; height: 46px; left: 40px; top: 308px; position: absolute; color: black; font-size: 14px; font-family: Itim; font-weight: 400; word-wrap: break-word">Events to Register</div>
</div>
```
## Frame5:
```
<div style="width: 222px; height: 412px; position: relative; background: white">
  <img style="width: 222px; height: 412px; left: 0px; top: 0px; position: absolute" src="https://via.placeholder.com/222x412" />
  <img style="width: 200px; height: 23.67px; left: 11px; top: 13px; position: absolute" src="https://via.placeholder.com/200x24" />
  <div style="left: 27px; top: 99px; position: absolute; color: black; font-size: 32px; font-family: Irish Grover; font-weight: 400; word-wrap: break-word">THANK YOU</div>
  <div style="left: 2px; top: 165px; position: absolute"><span style="color: #E62323; font-size: 14px; font-family: Itim; font-weight: 400; word-wrap: break-word">“Looking forward to your energy and<br/> spirit at the sports events</span><span style="color: black; font-size: 14px; font-family: Itim; font-weight: 400; word-wrap: break-word">!"</span></div>
  <div style="left: 63px; top: 250px; position: absolute; color: black; font-size: 20px; font-family: Irish Grover; font-weight: 400; word-wrap: break-word">Contact us</div>
  <div style="left: 89px; top: 280px; position: absolute"><span style="color: black; font-size: 14px; font-family: Istok Web; font-weight: 400; word-wrap: break-word">E-</span><span style="color: black; font-size: 16px; font-family: Istok Web; font-weight: 400; word-wrap: break-word">ma</span><span style="color: black; font-size: 16px; font-family: Itim; font-weight: 400; word-wrap: break-word">il<br/></span></div>
  <div style="left: 52px; top: 301px; position: absolute; color: black; font-size: 14px; font-family: Istok Web; font-weight: 400; word-wrap: break-word">Sec@gmail.com</div>
  <div style="left: 55px; top: 321px; position: absolute; color: black; font-size: 14px; font-family: Istok Web; font-weight: 400; word-wrap: break-word">Phone Number</div>
  <div style="left: 65px; top: 341px; position: absolute; color: black; font-size: 14px; font-family: Itim; font-weight: 400; word-wrap: break-word">9632587412</div>
  <div style="left: 65px; top: 364px; position: absolute; color: black; font-size: 14px; font-family: Itim; font-weight: 400; word-wrap: break-word">7412589632</div>
</div>

```
## OUTPUT:
![image](https://github.com/user-attachments/assets/9132786c-3408-4390-84ee-8844f3316e85)
## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
