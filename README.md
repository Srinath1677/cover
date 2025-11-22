# Ex.05 Book Cover Page Design
## Date:

## AIM:
To design a book back cover page using HTML and CSS.

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
    <title>AI</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(Background.png);
            background-size: cover;
        }
            
        
        .insight{
            color:whitesmoke;
        
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:yellow;
            top:250px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:wheat;
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 10px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:300px;
            
        }
        .pub{
            color:whitesmoke;
            font-size: medium;
            position: relative;
            top:270px;
            left:330px;
        }
        .ed{
            color:whitesmoke;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:250px;
        
        }
        .subtitle{
            color:wheat;
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 250px;
            right:6px;
            width: 100px;
            height: 80px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                ARTIFICIAL INTELLIGENCE
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1>POWER OF AI !</h1></div>
            <div class="subtitle">
                 
            </div>
            <div class="subtitle">
                 Artificial intelligenceis not a 
               subtitute for human intelligence;it is a tool
              to amplify human creativity and ingenuity
            </div>

            <div class="mypic">
                <img src="Photo.jpg" width="90" height="100" align="bottom"></img>
            </div>
            <div class="id">
                <hr style="color:blanchedalmond">
            </div>
            <div class="author">
               <p><b>C Dharshan</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>SPECIAL EDITION</b>
            </div>
        </div>
        </body>
        
</html>
```

## OUTPUT:
![ffc1e466-3d4a-43a8-b115-822c615eb031](https://github.com/user-attachments/assets/f898ed22-1bcc-432a-af37-72b09af05298)


## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
