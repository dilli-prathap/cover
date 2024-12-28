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
    <title>Book Cover Design</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background-color: #f2f2f2;
            font-family: Arial, sans-serif;
        }
        .book-cover {
            width: 350px;
            height: 550px;
            background: linear-gradient(to bottom right, #2c3e50, #4ca1af);
            color: white;
            text-align: center;
            position: relative;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 8px 12px rgba(0, 0, 0, 0.3);
        }
        .expert-insight {
            font-size: 14px;
            font-weight: bold;
            color: #f39c12;
            border-bottom: 2px solid #e67e22;
            display: inline-block;
            padding-bottom: 5px;
        }
        .book-title {
            font-size: 28px;
            font-weight: bold;
            margin: 30px 0 10px 0;
            line-height: 1.3;
        }
        .subtitle {
            font-size: 16px;
            color: #dfe6e9;
            margin-bottom: 40px;
        }
        .bottom-section {
            position: absolute;
            bottom: 20px;
            width: 100%;
            text-align: center;
        }
        .edition {
            font-weight: bold;
            font-size: 14px;
            color: #f39c12;
        }
        .author-image {
            margin: 10px auto;
            width: 70px;
            height: 70px;
            border-radius: 50%;
            border: 3px solid #f39c12;
            object-fit: cover;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.5);
        }
        .author-name {
            margin-top: 10px;
            font-size: 16px;
            font-weight: bold;
            color: #ecf0f1;
        }
    </style>
</head>
<body>
    <div class="book-cover">
        <div class="expert-insight">EXPERT INSIGHT</div>
                <div class="book-title">
            ARTIFICIAL INTELLIGENCE <br> AND MACHINE LEARNING <br> FOR CODERS
        </div>
        <div class="subtitle">From BigData to SmallData</div>
        <div class="bottom-section">
            <div class="edition">SECOND EDITION</div>
            <img src="cover.jpeg" alt="Author Image" class="author-image">
            <div class="author-name">Moroney, Laurence</div>
        </div>
    </div>
</body>
</html>

```
## OUTPUT:
![Screenshot 2024-12-28 090437](https://github.com/user-attachments/assets/31adbe58-329a-403d-9379-729f0c56ab0f)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
