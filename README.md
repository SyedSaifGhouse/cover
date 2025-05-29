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
<html lang="en">
<head>
    <style>
        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            font-family: 'Georgia', serif;
            background linear-gradient(135deg, #f3e5ab, #e8d094);
           
        }
        .book-cover {
            width: 470px;
            height: 650px;
            background-image: url('bg.png');
            border: 4px solid brown;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            padding: 30px;
            text-align: center;
        }
        .title {
            font-size: 50px;
            font-weight:bolder;
            color: #ffffff;
            font-family: "BankGothic MD BT";
            background-color: rgb(134, 2, 28); opacity: 100%;
        }
        .author {
            font-size: 29px;
            margin-top 10px;
            color:black;
            background: linear-gradient(to right,rgb(255, 2255, 255, 0.5),rgb(134, 2, 28, 0.5));
            font-family: "Times New Roman";
            font-weight: 900;
            text-align: right;
        }
        .image{
            width: 100px; text-align: center;
        }
        .Author{
            
            width: 100px;
           float: right; 
        }
        .images{
            display: flex;
            width: 5px;
        }
        .about{
            letter-spacing: 2px;
            color: black;
            font-weight: 400;
            background-color: white; opacity: 100%;
        }
        .publisher {
            font-size: 18px;
            color: #6b4f3f;
        }
        .cover-design {
            margin-top: 0px;
            background-image: url('author.png');
            background-size: cover;
            background-position: center;
            height: 210px;
            border: 1px solid #b5651d;
        }
        .about2{
            font-weight: 200;
            font-style: italic;
            background-color: white;opacity:100%;
        }
        .about2sub{
            letter-spacing: 1px;
            font-weight: 500;
            font-size:medium;
            background-color: white;opacity:100%;
        }
        .footer {
            font-size: 14px;
            margin-top: 0px;
            color: whitesmoke;
            font-family: "Caveat", cursive;
            justify-content: center;
            width: 470px;
            height: 20px;
            background-color: rgb(134, 2, 28); opacity: 90%;
}
    </style>
</head>
<body>

    <div class="book-cover">
        <div class="title">BASICS OF PYTHON PROGRAMMING</div>
        <div class="author"> ~GUIDO VAN ROSSUM</div>
        
        <div class="cover-design"></div>
        <div class="about">LESSONS FOR BEGINNERS TO PROFESSIONALS </div>
        <h3 class="about2">"Programming is not a science.Its a CRAFT" </h3>
        <h2 class="about2sub">-RICHARD STALLMAN </h2>
        <div class="footer">Best Selling Book for PYTHON PRG</div>
    </div>

</body>
</html

~~~
# OUTPUT:
![image](https://github.com/user-attachments/assets/d88bfe87-2ee3-4681-b85e-cb182892425e)
![image](https://github.com/user-attachments/assets/a3775544-c648-48fd-8b65-06e38700f807)
![image](https://github.com/user-attachments/assets/34b2fece-7a9b-41b3-886c-f978000dd228)



# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
