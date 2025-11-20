### NAME: SURYA P <br>
### REG NO: 212224230280 <br> 
### Date: 16/10/2025

## EX. No. 6 : BOOK COVER DESIGN

## AIM :
To design a book front cover page using HTML and CSS.

## DESIGN STEPS :

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

## PROGRAM :

### HTML : 

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fundamentals of Web Application Development - Book Cover</title>
    <link rel="stylesheet" href="ex6.css">
</head>
<body>
    <div class="center-container">
        <div class="book-cover">
            
            <div class="background-gradient"></div>
            
            <div class="red-border"></div>

            <div class="top-header">
                <p class="sec-insights">SEC Insights</p>
                <hr class="header-line">
            </div>

            <div class="main-title">
                <h1>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</h1>
            </div>

            <div class="details-section">
                <p class="deep-dive">Deep Dive in HTML, CSS & JS Basics</p>
                <p class="top-seller">Top seller of 2025</p>
            </div>
            
            <div class="special-edition">
                SPECIAL EDITION
            </div>
            
            <div class="bottom-section">
                <p class="author-name">SURYA P</p>
                <img src="surya.png" alt="Author Photo" class="author-photo">
            </div>
        </div>
    </div>
</body>
</html>

```

### CSS :

```css
/* Basic Setup and Centering */
body {
    margin: 0;
    padding: 0;
    font-family: 'Times New Roman', Times, serif; /* Font choice to simulate the style */
    background-color: #e0e0e0; 
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
}

.book-cover {
    position: relative;
    width: 450px; /* Cover dimensions adjusted for a modern look */
    height: 650px;
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.4);
    overflow: hidden;
    color: white; /* Default text color is white */
}

/* --- Background and Border --- */
.background-gradient {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    /* Simulating the warm orange/red glow from the image */
    background: radial-gradient(circle at 50% 10%, #00d5ff, #0072a3, #001172);
    opacity: 0.9;
}

.red-border {
    position: absolute;
    top: 10px;
    left: 10px;
    right: 10px;
    bottom: 10px;
    border: 3px solid #ffd000; /* Bright Red Border */
    z-index: 5;
}

/* --- Top Header (SEC Insights) --- */
.top-header {
    position: absolute;
    top: 30px;
    left: 40px;
    z-index: 10;
}

.sec-insights {
    font-size: 1.1em;
    font-weight: normal;
    margin: 0;
    padding: 0;
}

.header-line {
    border: 0;
    border-top: 1px solid white;
    width: 100px; /* Line width to match the sample */
    margin: 3px 0 0 0;
}

/* --- Main Title --- */
.main-title {
    position: absolute;
    top: 150px; /* Positioned significantly down */
    left: 40px;
    right: 40px;
    z-index: 10;
}

.main-title h1 {
    font-size: 2.5em;
    font-weight: 700;
    line-height: 1.2;
    margin: 0;
    /* Font color simulation: slightly off-white for contrast */
    color: #fffaf0; 
}

/* --- Subtitle/Details Section --- */
.details-section {
    position: absolute;
    top: 360px; /* Positioned below the main title */
    left: 40px;
    z-index: 10;
    line-height: 1.4;
}

.deep-dive {
    font-size: 1.1em;
    margin: 0;
    font-weight: 500;
}

.top-seller {
    font-size: 0.9em;
    margin: 5px 0 0 0;
    color: #e0e0e0; /* Slightly muted */
}

/* --- Special Edition Tag --- */
.special-edition {
    position: absolute;
    bottom: 80px;
    left: 40px;
    font-size: 1em;
    font-weight: bold;
    color: white;
    z-index: 10;
}

/* --- Bottom Section (Author & Logo) --- */
.bottom-section {
    position: absolute;
    bottom: 30px;
    left: 40px; /* Author Name aligned left */
    right: 40px; /* SEC aligned right */
    height: 50px;
    z-index: 10;
}

.author-name {
    position: absolute;
    bottom: 0;
    left: 0;
    font-size: 1.1em;
    font-weight: bold;
    margin: 0;
}

.logo-text {
    position: absolute;
    bottom: 0;
    right: 0;
    font-size: 1.5em;
    font-weight: 900;
    margin: 0;
    color: #fff;
}

.author-photo {
    /* Photo is positioned on the bottom right corner, above the bottom text */
    position: absolute;
    right: 0;
    bottom: 10px; 
    width: 90px;
    height: 120px; /* Rectangular shape as in the image */
    background-color: white; /* To simulate the cutout/background */
    object-fit: contain; /* Ensure the image fits */
    padding: 5px; /* Padding for the white background effect */
    box-sizing: border-box;
    z-index: 10;
}
```

## OUTPUT :

<img width="555" height="804" alt="Screenshot 2025-11-20 113943" src="https://github.com/user-attachments/assets/0803a21b-f412-4a4e-98ce-4119b5793410" />

## RESULT :

The program for designing book front cover page using HTML and CSS is completed successfully.
