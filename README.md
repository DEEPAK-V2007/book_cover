# Ex.06 Book Front Cover Page Design
# Date:05-10-25
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
{% load static %}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BookCover</title>
    <style>
        body{
            display: flex;
            margin: 0;
            height: auto;
            justify-content: center;
            align-items: center;

        }
        .BookCover{
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: space-between;
            background: url('{% static "wing.jpg" %}') center/cover no-repeat;
            color: white;
            height: 600px;
            width: 360px;
            padding: 90px;
            font-size: x-large;
        }
        h1{
            margin-bottom: 150px;
            text-transform: uppercase;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        }
        img{
            border-radius: 50%;
            border: 10px,solid white;
            margin-top: 130px;
            margin-left: 300px;
        }
        h6{
            margin-left: 180px;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            text-transform: uppercase;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <div class="BookCover">
        <h1><b><u>Wings of Fire</u></b></h1>
        <img src="{% static 'APJ.jpg' %}">
        <h6>- an autobiography of Dr A.P.J.Abdul Kalam</h6>
    </div>
</body>
</html>
```
# OUTPUT:

![alt text](<EX6 output.png>)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
