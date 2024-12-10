# Ex.06 Book Front Cover Page Design
## Date:8-12-2024

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
    <title>Inspirational Journey</title>
    <style>
        .bookpage {
            width: 400px;
            height: 600px;
            color: rgb(14, 180, 230);
            margin-left: auto;
            margin-right: auto;
            padding: 30px;
            font-family: 'Arial, sans-serif';
            background-image:url("bg.jpg");
            background-size: cover;
        }

        .insight {
            color: black;
            top: 200px;
            
        }

        .hrstyle {
            width: 90px;
        }

        .author {
            display: inline;
            position: relative;
            color: rgb(9, 8, 8);
            top: 250px;
            font-family: Georgia;
            font-size: medium;
        }

        .booktitle {
            color: red;
            font-family: Roquen;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        }

        .id {
            width: 400px;
            position: relative;
            top: 250px;
        }

        .pub {
            color: rgb(22, 22, 22);
            font-size: medium;
            font-family: Georgia;
            position: relative;
            top: 200px;
            left: 305px;
        }

        .ed {
            color: blue;
            font-size: medium;
            font-family: Verdana;
            position: relative;
            top: 150px;
        }

        .subtitle {
            color: rgb(8, 9, 9);
            font-family: unicorn;
            font-size: x-large;
            position: relative;
            top: 50px;
        }

        .mypic {
            position: relative;
            top: 230px;
            left: 260px;
            width: 90px;
            height: 80px;
            background-size: contain;
        }
    </style>
</head>

<body>
    <div class="bookpage">
        <div class="insight">
            INSPIRE
        </div>
        <div class="hrstyle">
            <hr style="color: blue;">
        </div>
        <div class="booktitle">
            <h1 style="font-family: cursive; color: rgb(217, 147, 16);">A Developer's Guide</h1>
        </div>
        <div class="subtitle" style="text-align: center;color: red;">
            Modern Web Applications
        </div>
        <div class="subtitle" style="color: rgb(193, 172, 133);text-align: center;">
            Top Seller of 2023
        </div>

        <div class="mypic">
            <img src="photo.png" width="120" height="100">
        </div>
        <div class="id">
            <hr style="color: rgb(65, 221, 9)">
        </div>
        <div class="author">
            <p><b>JASH</b></p>
        </div>
        <div class="pub">
            MIRZHA
        </div>
        <div class="ed">
            <b>SPECIAL EDITION</b>
        </div>
    </div>
</body>

</html>

```

## OUTPUT:
![alt text](<Screenshot (133).png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
