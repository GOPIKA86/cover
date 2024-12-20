# Ex.06 Book Front Cover Page Design
## Date:03/12/2024

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
<!DOCTYPE html>
<html>

<head>
    <title>Book cover</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:violet;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: ' Arial, sans-serif';
            background-image: url("bg.jpg");
            background-size: cover;
        }
            
        
        .insight{
            color:azure;
        
        }
        
        
        .hrstyle{
            width:150px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:red;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:azure;
            font-family: arial;
            font-size: xx-larger;
            text-align: center;
            position: relative;
            top: 10px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            color:red;
            font-size: medium;
            position: relative;
            top:160px;
            left:330px;
        }
        .ed{
            color:white;
            font-size: medium;
            font-family:sans-serif;
            position:relative;
            top:85px;
        
        }
        .subtitle{
            color:azure;
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:10px;
        }
        .mypic{
            position: relative;
            top: 160px;
            left: 280px;
            width: 90px;
            height: 80px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                EXPERT INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color:white;">
            </div>
            <div class="booktitle">
                <h1 style="font-family: georgia; color:wheat;">BEYOND CODE: THE POWER OF WEB FRAMEWORKS</h1></div>
            <div class="subtitle" style="text-align: center;color: beige;">
                Unlocking Efficiency and Innovation in Web Development
            </div>
            <div class="subtitle" style="color:orange;text-align: center;">
                 
            </div>

            <div class="mypic">
                <img src="gopika.jpg" width="120" height="100" >
            </div>
            <div class="id">
                <hr style="color:blanchedalmond">
            </div>
            <div class="author">
               <p><b>GOPIKA A</b></p>
            </div>
            <div class="pub">
              MANASA
            </div>
            <div class="ed">
                <b>FIFTH EDITION</b>
            </div>
        </div>
        </body>
</html>
```

## OUTPUT:
![alt text](<Screenshot (19).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
