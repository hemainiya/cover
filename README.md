# Ex.06 Book Front Cover Page Design
## Date:22/05/25

## AIM:
To design a book front cover page using HTML and CSS.

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
'''
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #000;
      font-family: 'Georgia', serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .image-container {
      position: relative;
      width: 400px;
      height: 600px;
      overflow: hidden;
    }

    .image-container img.cover {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    .centered-title {
      position: absolute;
      top: 12%;
      left: 50%;
      transform: translate(-50%, -50%);
      color: black;
      font-size: 28px;
      font-weight: bold;
      text-align: center;
      text-shadow: 1px 1px 2px white;
    }

    .subtitle {
      font-size: 18px;
      font-weight: normal;
      color: black;
      text-shadow: 1px 1px 2px white;
    }

    .quote {
      position: absolute;
      top: 52%;
      left: 50%;
      transform: translate(-50%, -50%);
      color: black;
      font-size: 17px;
      width: 85%;
      text-align: center;
      text-shadow: 1px 1px 2px white;
    }

    .author-name {
      position: absolute;
      bottom: 20px;
      left: 25px;
      font-size: 20px;
      color: black;
      font-weight: bold;
      text-shadow: 1px 1px 2px white;
    }

    .author-image {
      position: absolute;
      bottom: 15px;
      right: 15px;
    }

    .author-image img {
      width: 90px;
      height: 90px;
      border-radius: 10px;
      object-fit: cover;
      box-shadow: 0 0 5px white;
    }
  </style>
</head>
<body>
  <div class="image-container">
    <img class="cover" src="cover2.jpeg" alt="Book Cover">

    <div class="centered-title">
      MIND
      <div class="subtitle">MASTERING MINDFULNESS</div>
    </div>

    <div class="quote">
      "The present moment is the only time we have."
    </div>

    <div class="author-name">DYLAN</div>

    <div class="author-image">
      <img src="author.png" alt="Author">
    </div>
  </div>
</body>
</html>
'''


## OUTPUT:
![alt text](image-1.png)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
