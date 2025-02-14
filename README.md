# Ex.06 Book Front Cover Page Design
## Date:01.12.23

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
        .bookpage{

            width: 400px;
            height: 650px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(cover1.jpg);
            background-size: cover;
        }
            
        
        .insight{
            color:bisque;
        
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:rgb(212, 212, 22);
            top:280px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:aqua;
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 25px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:280px;
           
        }
        .pub{
            color:cornflowerblue;
            font-size: medium;
            position: relative;
            top:250px;
            left:330px;
        }
        .ed{
            color:greenyellow;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:180px;
        
        }
        .subtitle{
            color:aquamarine;
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 60px;
        }
        .mypic{
            position: relative;
            top: 275px;
            left: 320px;
            width: 70px;
            height: 80px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
         background-image: url(img.jpg);
        <div class="bookpage">
            <div class="insight">
                COMPUTER
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1>FUNDAMENTALS of COMPUTERS</h1></div>
            <div class="subtitle">
                 BEGINNERS CRASH COURSE [Day 1 to Day 100]
                 <br>
                 CODING DATA, PYTHON,ALGORITHMS AND HACKING.
                </div>
            
            <div class="mypic">
                <img src="pic1.jpeg" width="70" height="80" >
            </div>
            <div class="id">
                <hr style="color:rgb(13, 128, 0)">
            </div>
            <div class="author">
               <p><b>SARANYA V</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>FIRST EDITION</b>
            </div>
        </div>
        </body>
</html>
```

## OUTPUT:
![Alt text](BookCoverPage.png)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
