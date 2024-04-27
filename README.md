# Ex.06 Book Front Cover Page Design
## Date:27/04/24

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
<!DOCTYPE html>>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style> 
    .img{<!
        background-color: olivedrab;
        margin-left: 35%;
        width: 500px;
        height: 700px;
    }
    .head{
        position: absolute;
        top:50%;
        right: 37.5%;
        font-size: medium;
        
    }
    .title{
        position:absolute;
        top:55%;
        right:35%;
        font-size: large;

    }
    .author{
        position:absolute;
        top:74%;
        right:35%;
        font-size:small
    }
    .image{
        position:absolute;
        top: 28%;
        left:55%;
        border-radius: 45%;
    }
    </style>
    </head>
    <body>
        <div class="bookpage">
            <div class="img"></div>

        <div class="head">
        <h5>
            By Jacqueline sing
        </h5>
        </div>
        <div class="title">
            <h1>
                THE<br>DESIGN<br>HUSTLE<br>
            </h1>
        </div>
        <div class="author">
            <h3>
                Tips & Tricks For<br>Design Enterpreneurs<br>
            </h3>
        </div>
        <div class="image">
            <img src="21500569 - Copy.jpg" width="126">
        </div>
    </div>
    </body>
    </html>
```
## OUTPUT:
![Screenshot (133)](https://github.com/selvasachein/cover/assets/131433133/4a6850f7-e154-49bf-b519-573eb54e1540)
## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
