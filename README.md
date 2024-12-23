# Ex.06 Book Front Cover Page Design
## Date:

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
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Front Page</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@500&family=Poppins:wght@600&display=swap" rel="stylesheet">
    
    <style>
        /* Reset default margins and padding */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* General Body Styling */
        body {
            font-family: 'Poppins', sans-serif;
            background: #050506;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        /* Book Cover Styling */
        .book-cover {
            position: relative;
            width: 700px;
            height: 500px;
            background: #3987ec;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(13, 89, 229, 0.916);
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 40px;
            overflow: hidden;
        }

        /* Book Title Styling */
        .book-title {
            font-family: 'Montserrat', sans-serif;
            font-size: 40px;
            font-weight: bold;
            color: #f9f8fc;
            margin-top: 20px;
            text-align: center;
        }

        /* Content Section (Middle of the Page) */
        .book-content {
            text-align: center;
            margin-top: 60px; /* Adjust the spacing from the title */
        }

        .book-description p {
            font-size: 18px;
            font-style: italic;
            opacity: 0.8;
            color: #e9e8f2;
            max-width: 80%; /* Keep content width in check */
            margin: 20px auto;
        }

        /* Horizontal Line (extends from left till the image) */
        .horizontal-line {
            width: calc(100% - 200px); /* Leaves space for the image on the right */
            height: 2px;
            background-color: #ec200d;
            position: absolute;
            bottom: 110px; /* Place it above the author and image */
            left: 0;
        }

        /* Image Container (Bottom Right) */
        .image-container {
            position: absolute;
            bottom: 20px;
            right: 20px;
        }

        /* Image Styling */
        .book-image {
            width: 180px;
            height: auto;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(221, 38, 38, 0.732);
            border: 5px solid #f41616e2;
        }

        /* Author Name Styling */
        .book-author {
            position: absolute;
            bottom: 80px; /* Space just above the image */
            text-align: center;
            width: 100%;
        }

        .book-author h2 {
            font-size: 24px;
            font-weight: 600;
            color: #f3eded;
        }
    </style>
</head>
<body>
    <div class="book-cover">
        <!-- Book Title -->
        <div class="book-title">
            <h1>WELCOME TO</h1>
        </div>

        <!-- Content Section (Middle) -->
        <div class="book-content">
            <div class="book-description">
                <h2>WEB APPLICATION</h2>
            </div>
        </div>

        <!-- Horizontal Line (Extends from left till the image) -->
        <div class="horizontal-line"></div>

        <!-- Author Name Below the Content -->
        <div class="book-author">
            <h2>by DILLI PRATHAP</h2>
        </div>

        <!-- Image at Bottom-Right -->
        <div class="image-container">
            <img src="pic.png"alt="Book Image" class="book-image">
        </div>
    </div>
</body>
</html>

```
## OUTPUT:
![alt text](<Screenshot 2024-12-23 202637.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
