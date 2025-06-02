# Ex.06 Book Front Cover Page Design
# Date:
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
~~~
<!DOCTYPE html>
<html>
<head>
    <title>My Cover</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: #000;
        }

        .bookpage {
            width: 400px;
            height: 600px;
            margin: 30px auto;
            padding: 20px;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: #fff;
            background-image: url('background.jpg'); /* Change to your image name */
            background-size: cover;
            background-position: center;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.6);
            position: relative;
            border-radius: 15px;
        }

        .insight {
            color: #ffa500;
            font-size: 20px;
            text-align: center;
            font-weight: bold;
        }

        .hrstyle hr {
            width: 50%;
            margin: 10px auto;
            border: 1px solid #ff66cc;
        }

        .booktitle h1 {
            text-align: center;
            font-family: 'Courier New', Courier, monospace;
            font-style: oblique;
            color: #fffacd;
            margin-top: 30px;
        }

        .subtitle {
            color: #e0f7fa;
            text-align: center;
            font-size: 18px;
            margin-top: 10px;
        }

        .mypic img {
            position: absolute;
            bottom: 20px;
            right: 20px;
            width: 100px;
            height: 120px;
            object-fit: cover;
            border: 2px solid #fff;
            border-radius: 10px;
        }

        .author {
            position: absolute;
            bottom: 100px;
            left: 20px;
            font-family: cursive;
            color: #ffb6c1;
        }

        .pub {
            position: absolute;
            bottom: 60px;
            left: 20px;
            font-size: 14px;
            color: #ff4d4d;
        }

        .ed {
            position: absolute;
            bottom: 40px;
            left: 20px;
            font-size: 14px;
            color: #fdfd96;
            font-weight: bold;
        }

        .id hr {
            border-color: #daa520;
            width: 90%;
            margin: 50px auto 0;
        }
    </style>
</head>
<body>
    <div class="bookpage">
        <div class="insight">SAVIEANS WORK</div>
        <div class="hrstyle"><hr></div>
        <div class="booktitle"><h1>WEB DEVELOPMENT</h1></div>
        <div class="subtitle">Learn WEB from the expert</div>
        <div class="mypic"><img src="my.jpg" alt="Author's Photo"></div>
        <div class="id"><hr></div>
        <div class="author"><b>SYED SAIF</b></div>
        <div class="pub">SEC</div>
        <div class="ed">3rd Edition</div>
    </div>
</body>
</html>


~~~
# OUTPUT:
![image](https://github.com/user-attachments/assets/1b2bf390-16d2-4d19-81a8-3f4b684efa73)




# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
