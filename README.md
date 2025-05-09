# Ex.08 Design of Interactive Image Gallery
# Date:
# AIM:
To design a web application for an inteactive image gallery with minimum five images.

# DESIGN STEPS:
## Step 1:
Clone the github repository and create Django admin interface.

## Step 2:
Change settings.py file to allow request from all hosts.

## Step 3:
Use CSS for positioning and styling.

## Step 4:
Write JavaScript program for implementing interactivity.

## Step 5:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# PROGRAM:
'''
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MY GALLERY</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #e8eeef;
    }

    .gallery-container {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      padding: 20px;
      justify-content: center;
    }

    .gallery-item {
      width: 200px;
      height: 150px;
      overflow: hidden;
      cursor: pointer;
      border-radius: 8px;
      box-shadow: 0 4px 6px rgba(12, 215, 93, 0.1);
    }

    .gallery-item img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      transition: transform 0.3s ease;
    }

    .gallery-item:hover img {
      transform: scale(1.1);
    }

    .lightbox {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(0, 0, 0, 0.8);
      display: none;
      align-items: center;
      justify-content: center;
      z-index: 1000;
    }

    .lightbox-image {
      max-width: 90%;
      max-height: 90%;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(223, 123, 8, 0.252);
    }

    .close {
      position: absolute;
      top: 20px;
      right: 30px;
      font-size: 30px;
      color: #fff;
      cursor: pointer;
      z-index: 1001;
    }

    .close:hover {
      color: #ff6b6b;
    }
    .footer {
        text-align: center;
        margin-top:40%;
        background-color: bisque;
        color:black;
        font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        font-size: 30px;
    }
  </style>
</head>
<body>
    <center>
  <div class="gallery-container">
    <div class="gallery-item">
      <img src="c:\Users\admin\Downloads\dog1.jpg" alt="Image 1">
    </div>
    <br>
    <div class="gallery-item">
      <img src="c:\Users\admin\Downloads\dog2.jpeg" alt="Image 2">
    </div>
    <br>
    <div class="gallery-item">
      <img src="c:\Users\admin\Downloads\dog3.jpg" alt="Image 3">
    </div>
    <br>
    <div class="gallery-item">
        <img src="c:\Users\admin\Downloads\dog4.jpg" alt="Image 4">
    </div>
    <br>
    <div class="gallery-item">
        <img src="c:\Users\admin\Downloads\dog5.avif" alt="Image 5">
    </div>
    <br>
    <div class="gallery-item">
        <img src="c:\Users\admin\Downloads\dog6.jpg" alt="Image 6">
    </div>
</center>
    <br>
    </div>
  <div class="lightbox">
    <span class="close">&times;</span>
    <img class="lightbox-image" src="" alt="Enlarged Image">
  </div>
  <div class="footer">
  </div>

</body>

</html>
'''

# OUTPUT:
![Screenshot 2025-05-09 210202](https://github.com/user-attachments/assets/9c7fb221-3b14-46b8-9d57-88364765540a)


# RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
