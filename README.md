# Ex.05 Book Cover Page Design
## Date:17/12/2025

## AIM:
To design a book back cover page using HTML and CSS.

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
cover.html
<html>
    <head>
        <title>About the Book</title>
        <link href="style.css" rel="stylesheet">
    </head>
    <body>

        <div class="cover">
            <div class="heading">
                <h1>ABOUT THE BOOK</h1>
                <hr>
            </div>
            <div class="info">
                <p>
                    Mastering C is the crucial first step toward understanding how software truly works. This book provides a clear, comprehensive, and practical introduction to the language that powers operating systems and embedded devices worldwide.

Designed for absolute beginners and computer science students alike, Fundamentals of C demystifies complex topics, including pointers, data structures, and efficient memory management. You will progress from the basic syntax to writing robust, clean, and optimized code.

Start your coding journey with confidence. Build a foundation that will last, paving the way for mastering C++, Python, and beyond.
                </p>
            </div>
            <div class="quoteword">
                <p>
                    "To understand the computer, you must first understand C."
                    <br>
                    "Clarity is the greatest strength of any code."
                </p>
            </div>

            <div class="aboutauthor">
            <div class="picture">
            <img src="author.JPG"  alt="Author Photo" class="img">
            </div>

            <div class="author">
            <h3>SYED MEERAN A</h3>
            <p>
                Syed Meeran A is a seasoned professional and dedicated educator. He provides students and self-learners a clear, practical path to mastering C, the fundamental language of all modern computing.
            </p>
        </div>
        </div>
        <div class="last">
            <div class="bottom">
            <h4>SEC PUBLISHERS</h4>
            <p>Printed in Tamil Nadu</p>
            </div>

            <div class="price">Price: rs.600</div>
         </div>
</body>
</html>


        </div>
        </div>

    </body>
</html>
style.css
body {
    margin: 0;
    padding: 0;
    font-family: Georgia, serif;
    color:rgb(255, 255, 255);
}
.cover {
    width: 720px;
    height: 1000px;
    margin: 20px auto;
    background-image: url("img1.png");
    background-size: cover;
    background-position: center;
    box-sizing: border-box;
    padding: 20px;
    border: 1px solid white;
}
.heading{
    text-align: left;
    font-size: 30px;
    margin-top: 40px;
}
.info {
    font-size: 20px;
    font-weight: light;
    color: light white;
    margin-top: 10px;
    
}
.quoteword {
    text-align: center;
    font-family: 'Gill Sans', 'Gill Sans MT', 'Calibri', 'Trebuchet MS', sans-serif;
    background-color: rgb(159, 31, 31);
    border-left: 5px solid blueviolet;
    margin-top: 30px;
    margin-bottom: 30px;
    font-size: 25px;
    
}
.aboutauthor{
    display: flex;
    background-color: rgb(192, 156, 156);
}

.picture{
    height: 130px;
    width: 110px;
    display: flex;
    padding: 10px;
}



.author{
    margin-left: 20px;
    font-size: 13px;
}

.last{
    background-color: lightcoral;
    margin-top: 150px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 2px;
}

.bottom{
    margin-left: 20px;
}

.price{
    color: white;
    font-size: 25px;
    margin-right: 25px;
}
```


## OUTPUT:
![alt text](<Screenshot (28).png>)


## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
