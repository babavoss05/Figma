# Ex09 Event Registration Web Application
## Date: 14/5/24

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
### page 1:
``` html
<img style="width: 750px; height: 360px; transform: rotate(90deg); transform-origin: 0 0" src="https://via.placeholder.com/750x360" />
```
### page 2:
``` html
<div style="width: 360px; height: 742px; position: relative; background: white">
  <img style="width: 360px; height: 640px; left: 0px; top: 0px; position: absolute" src="https://via.placeholder.com/360x640" />
  <div style="width: 208px; height: 40px; padding-left: 16px; padding-right: 16px; padding-top: 8px; padding-bottom: 8px; left: 76px; top: 300px; position: absolute; background: white; border-radius: 8px; border: 1px #E0E0E0 solid; justify-content: flex-start; align-items: center; gap: 16px; display: inline-flex">
    <div style="flex: 1 1 0; color: #828282; font-size: 16px; font-family: Inter; font-weight: 400; line-height: 24px; word-wrap: break-word">Select an event<br/></div>
    <div style="width: 24px; height: 24px; position: relative">
      <div style="width: 12px; height: 6px; left: 6px; top: 9px; position: absolute; border: 2px #828282 solid"></div>
    </div>
  </div>
  <div style="height: 40px; padding-left: 16px; padding-right: 16px; left: 137px; top: 518px; position: absolute; background: #EEEEEE; border-radius: 8px; justify-content: center; align-items: center; gap: 8px; display: inline-flex">
    <div style="color: black; font-size: 16px; font-family: Inter; font-weight: 500; line-height: 24px; word-wrap: break-word">Submit</div>
  </div>
  <div style="width: 217px; height: 47px; left: 83px; top: 400px; position: absolute; justify-content: flex-start; align-items: flex-start; display: inline-flex">
    <div style="padding: 4px; background: #F7F7F7; border-radius: 8px; justify-content: flex-start; align-items: flex-start; display: flex">
      <div style="width: 40px; padding-left: 12px; padding-right: 12px; background: white; box-shadow: 0px 1px 2px rgba(0, 0, 0, 0.05); border-radius: 4px; justify-content: flex-start; align-items: center; gap: 8px; display: flex">
        <div style="color: black; font-size: 16px; font-family: Inter; font-weight: 500; line-height: 24px; word-wrap: break-word">AI</div>
      </div>
      <div style="width: 87px; padding-left: 12px; padding-right: 12px; border-radius: 4px; justify-content: flex-start; align-items: center; gap: 8px; display: flex">
        <div style="color: black; font-size: 16px; font-family: Inter; font-weight: 500; line-height: 24px; word-wrap: break-word">DevOPS</div>
      </div>
      <div style="width: 69px; padding-left: 12px; padding-right: 12px; border-radius: 4px; justify-content: flex-start; align-items: center; gap: 8px; display: flex">
        <div style="color: black; font-size: 16px; font-family: Inter; font-weight: 500; line-height: 24px; word-wrap: break-word">Cloud</div>
      </div>
    </div>
  </div>
</div>
```
### page 3:
``` html
<div style="width: 360px; height: 640px; position: relative; background: white">
  <img style="width: 360px; height: 612px; left: -8px; top: 29px; position: absolute" src="https://via.placeholder.com/360x612" />
  <div style="width: 311px; height: 42px; padding-left: 16px; padding-right: 16px; padding-top: 8px; padding-bottom: 8px; left: 16px; top: 139px; position: absolute; background: white; border-radius: 8px; border: 1px #E0E0E0 solid; justify-content: flex-start; align-items: center; gap: 16px; display: inline-flex">
    <div style="flex: 1 1 0; color: #2A2828; font-size: 14px; font-family: Inter; font-weight: 400; line-height: 19.60px; word-wrap: break-word">Your name</div>
  </div>
  <div style="width: 311px; height: 42px; padding-left: 16px; padding-right: 16px; padding-top: 8px; padding-bottom: 8px; left: 16px; top: 208px; position: absolute; background: white; border-radius: 8px; border: 1px #E0E0E0 solid; justify-content: flex-start; align-items: center; gap: 16px; display: inline-flex">
    <div style="flex: 1 1 0; color: #2A2828; font-size: 14px; font-family: Inter; font-weight: 400; line-height: 19.60px; word-wrap: break-word">Mobile number</div>
  </div>
  <div style="width: 311px; height: 42px; padding-left: 16px; padding-right: 16px; padding-top: 8px; padding-bottom: 8px; left: 16px; top: 266px; position: absolute; background: white; border-radius: 8px; border: 1px #E0E0E0 solid; justify-content: flex-start; align-items: center; gap: 16px; display: inline-flex">
    <div style="flex: 1 1 0; color: #2A2828; font-size: 14px; font-family: Inter; font-weight: 400; line-height: 19.60px; word-wrap: break-word">Department</div>
  </div>
  <div style="width: 311px; height: 42px; padding-left: 16px; padding-right: 16px; padding-top: 8px; padding-bottom: 8px; left: 16px; top: 324px; position: absolute; background: white; border-radius: 8px; border: 1px #E0E0E0 solid; justify-content: flex-start; align-items: center; gap: 16px; display: inline-flex">
    <div style="flex: 1 1 0; color: #2A2828; font-size: 14px; font-family: Inter; font-weight: 400; line-height: 19.60px; word-wrap: break-word">Mobile Number</div>
  </div>
  <div style="width: 375px; padding-left: 24px; padding-right: 24px; left: -8px; top: 389px; position: absolute; flex-direction: column; justify-content: flex-start; align-items: center; gap: 24px; display: inline-flex">
    <div style="height: 96px; flex-direction: column; justify-content: flex-start; align-items: flex-start; gap: 16px; display: flex">
      <div style="align-self: stretch; height: 40px; padding-left: 16px; padding-right: 16px; padding-top: 8px; padding-bottom: 8px; background: white; border-radius: 8px; border: 1px #E0E0E0 solid; justify-content: flex-start; align-items: center; gap: 16px; display: inline-flex">
        <div style="flex: 1 1 0; color: #828282; font-size: 14px; font-family: Inter; font-weight: 400; line-height: 19.60px; word-wrap: break-word">email@domain.com</div>
      </div>
      <div style="align-self: stretch; height: 40px; padding-left: 16px; padding-right: 16px; background: black; border-radius: 8px; justify-content: center; align-items: center; gap: 8px; display: inline-flex">
        <div style="color: white; font-size: 14px; font-family: Inter; font-weight: 500; line-height: 19.60px; word-wrap: break-word">Sign up with email</div>
      </div>
    </div>
    <div style="width: 327px; justify-content: center; align-items: center; gap: 8px; display: inline-flex">
      <div style="flex: 1 1 0; height: 1px; background: #E6E6E6"></div>
      <div style="text-align: center; color: #828282; font-size: 14px; font-family: Inter; font-weight: 400; line-height: 19.60px; word-wrap: break-word">or continue with</div>
      <div style="flex: 1 1 0; height: 1px; background: #E6E6E6"></div>
    </div>
    <div style="width: 327px; height: 40px; position: relative; background: #EEEEEE; border-radius: 8px">
      <div style="left: 126px; top: 10px; position: absolute; justify-content: flex-start; align-items: center; gap: 8px; display: inline-flex">
        <div style="width: 20px; height: 20px; position: relative">
          <div style="width: 9.79px; height: 9.37px; left: 10.20px; top: 8.15px; position: absolute; background: #4285F4"></div>
          <div style="width: 15.86px; height: 7.99px; left: 1.09px; top: 11.94px; position: absolute; background: #34A853"></div>
          <div style="width: 4.40px; height: 9px; left: 0px; top: 5.44px; position: absolute; background: #FBBC05"></div>
          <div style="width: 15.93px; height: 7.99px; left: 1.09px; top: 0px; position: absolute; background: #EB4335"></div>
        </div>
        <div style="color: black; font-size: 14px; font-family: Inter; font-weight: 500; line-height: 19.60px; word-wrap: break-word">Google</div>
      </div>
    </div>
  </div>
</div>

```
### page 4:
``` html
<div style="width: 360px; height: 640px; position: relative; background: white">
  <img style="width: 1315px; height: 672px; left: 0px; top: 0px; position: absolute" src="https://via.placeholder.com/1315x672" />
  <div style="height: 40px; padding-left: 16px; padding-right: 16px; left: 135px; top: 336px; position: absolute; background: black; border-radius: 8px; justify-content: center; align-items: center; gap: 8px; display: inline-flex">
    <div style="color: white; font-size: 16px; font-family: Inter; font-weight: 500; line-height: 24px; word-wrap: break-word">Thank you!</div>
  </div>
</div>
```

## OUTPUT:
![alt text](<Screenshot 2024-05-14 204725.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
