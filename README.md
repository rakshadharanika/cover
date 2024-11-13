# Ex.06 Book Front Cover Page Design
### NAME  : V RAKSHA DHARANIKA 
### REG NO: 212223230167

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
```PY

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>The Young Wizard Book Cover</title>
  <style>
   
    .cover-container {
      position: relative;
      width: 400px;
      height: 600px;
      margin: 0 auto;
      color: white;
      font-family: 'Georgia', serif;
      overflow: hidden;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.6);
    }

    /* Background image styling */
    .cover-image {
      width: 100%;
      height: 100%;
      object-fit: cover;
      filter: brightness(1.3); /* Increase brightness */
    }

    /* Gradient overlay */
    .gradient-overlay {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: linear-gradient(to bottom, rgba(0, 0, 0, 0.1), rgba(0, 0, 0, 0.6)); /* Lighter overlay */
    }

    /* Author image styling */
    .author-image {
      position: absolute;
      top: 15px;
      left: 20px;
      width: 50px;
      height: 50px;
      border-radius: 50%;
      border: 2px solid goldenrod; /* Gold border around the image */
      box-shadow: 0 0 8px rgba(255, 215, 0, 0.8);
    }

    /* Title for the author at the top */
    .author-title {
      position: absolute;
      top: 20px;
      width: 100%;
      text-align: center;
      font-size: 1.5em;
      font-weight: bold;
      color: gold; /* Gold color for author text */
      font-family: 'Times New Roman', serif;
      letter-spacing: 2px;
      text-shadow: 0px 0px 8px rgba(255, 215, 0, 0.7);
    }

    /* Subtitle line below the author name */
    .subtitle-line {
      position: absolute;
      top: 50px;
      width: 40%; /* Adjust width for smaller line */
      left: 30%; /* Center align */
      border-top: 1px solid gold;
      opacity: 0.8;
    }

    /* Main book title */
    .main-title {
      position: absolute;
      bottom: 120px;
      width: 100%;
      text-align: center;
      font-size: 2.8em;
      font-weight: bold;
      color: orangered; /* Vibrant orange-red color for main title */
      letter-spacing: 3px;
      text-shadow: 0px 0px 12px rgba(255, 69, 0, 0.8), 2px 2px 6px black;
      font-family: 'Palatino', serif;
    }

    /* Subtitle below the main title */
    .series-title {
      position: absolute;
      bottom: 80px;
      width: 100%;
      text-align: center;
      font-size: 1.2em;
      color: lightgray;
      font-style: italic;
      letter-spacing: 1px;
      text-shadow: 1px 1px 4px black;
    }

    /* Name styling below the series title */
    .creator-name {
      position: absolute;
      bottom: 40px;
      width: 100%;
      text-align: center;
      font-size: 1.1em;
      color: white;
      font-weight: bold;
      font-family: 'Courier New', monospace;
      letter-spacing: 1px;
      text-shadow: 1px 1px 4px black;
    }
  </style>
</head>
<body>
  <div class="cover-container">
    <!-- Background image -->
    <img src="C:/Users/A.sathish/Downloads/WhatsApp Image 2024-11-13 at 15.31.02_85b797b6.jpg" alt="Book Cover Image" class="cover-image">
    
    <!-- Gradient overlay -->
    <div class="gradient-overlay"></div>

    <!-- Author's picture -->
    <img src="C:/Users/A.sathish/Downloads/WhatsApp Image 2024-11-13 at 15.54.57_3d74cd79.jpg" alt="Author Image" class="author-image">

    <!-- Author's name at the top -->
    <div class="author-title">AARON LOEB</div>
    <div class="subtitle-line"></div>

    <!-- Main book title -->
    <div class="main-title">THE YOUNG<br>WIZARD</div>

    <!-- Series title -->
    <div class="series-title">Mystic Fire Saga</div>

    <!-- Creator name -->
    <div class="creator-name">V RAKSHA DHARANIKA</div>
  </div>
</body>
</html>





```

## OUTPUT:
![image](https://github.com/user-attachments/assets/6cc66ee9-2954-46e7-9280-8e35d1085bab)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
