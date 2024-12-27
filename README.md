# Ex.06 Book Front Cover Page Design
## Date:
23-12-2024
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
    <style>
        /* Style for the body */
        body {
            margin: 0;
            height: 100vh;
            background-image: url("C:\Users\admin\OneDrive\Pictures\Screenshots\Screenshot 2024-12-19 143012.png"); /* Replace with your background image URL */
            background-size: cover;
            background-position: center;
            color: white;
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
        }

        /* Container for the book title and author */
        .book-container {
            position: relative;
            text-align: center;
        }

        /* Book title style */
        h1 {
            font-size: 4em;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
            margin: 0;
        }

        /* Subtitle style */
        h2 {
            font-size: 2em;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
            margin-top: 10px;
        }

        /* Author name style */
        p {
            font-size: 1.5em;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
            margin-top: 20px;
        }

        /* Style for the author's image */
        .author-img {
            position: absolute;
            right: 20px;
            bottom: 20px;
            width: 150px;
            height: auto;
            border-radius: 50%;
            border: 5px solid white;
        }
    </style>
</head>
<body>

    <div class="book-container">
        <h1>The Book Title</h1>
        <h2>A Subheading or Tagline</h2>
        <p>By Author Name</p>

        <!-- Author's image -->
        <img src="C:\Users\admin\OneDrive\Pictures\Screenshots\Screenshot 2024-12-23 192003.png" alt="Author Image" class="author-img"> <!-- Replace with your author image URL -->
    </div>

</body>
</html>


```
## OUTPUT:
![alt text](<Screenshot 2024-12-23 202637.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
