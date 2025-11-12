# Ex.06 Book Front Cover Page Design
## Date:

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<html>
    <head>
        <style>
            body {
                background-color: #f0f0f0;
            }
            img {
                margin-top: 50px;
                border: 5px solid #ccc;
                box-shadow: 2px 2px 12px rgba(0, 0, 0, 0.1);
                
            }
.bottom-left {
  position: absolute;
  bottom: 390px;
  left: 650px;
  color:#ffffff
}
.bottom-right {
  position: absolute;
  bottom: 380px;
  left: 950px;
  
}
        </style>
    </head>
    <body align="center">
        <img src="textbook.jpg" alt="Book Cover">
        <div class="bottom-left">Harshavardhan</div>
        <div class="bottom-right"><img src="harsha.jpg" style="width:50px; height:auto;"></div>
    </body>
</html>
```

## OUTPUT:
![alt text](image.png)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
