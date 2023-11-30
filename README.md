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
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <style type="text/css">
            .bookcover {
                width: 400px;
                height: 640px;
                color: rgb(0, 255, 42);
                margin-left: auto;
                margin-right: auto;
                padding: 20px;
                font-family: Arial, Helvetica, sans-serif;
                background-image: url(bg\ image.jpg);
                background-size: cover;
            }
            .insight {
                color: rgb(255, 255, 255);
            }
            .hr {
                width: 130px;
            }
            .h1 {
                font-size: larger;
                font-family: Arial, Helvetica, sans-serif;
                text-align: center;
                position: relative;
                top: 30px;
            }
            .p {
                font-size: medium;
                font-family: Arial, Helvetica, sans-serif;
                position: relative;
                top: 40px;  
            }
            .edition {
                font-size: large;
                font-family: Arial, Helvetica, sans-serif;
                color: rgb(12, 178, 243);
                top: 90px;
                position: relative;
            }
            .photo {
                position: relative;
                top: 150px;
                left: 250px;
                width: 100px;
                height: 100px;
                background-size: cover;
            }
            .hrstyle {
                position: relative;
                width: 400px;
                top: 200px;
            }
            .author {
                font-size: medium;
                font-family: Arial, Helvetica, sans-serif;
                display: inline;
                position: relative;
                color: rgb(249, 5, 5);
                top: 210px;
            }
            .publisher {
                font-size: large;
                position: relative;
                top: 180px;
                left: 330px;
            }
        </style>
        <title> Book Front Cover Page  </title>
    </head>
    <body>
        <div class="bookcover">
            <div class="insight">
                EXPERT INSIGHT
            </div>
            <div class="hr">
                <hr>
            </div>
            <div class="h1">
                <h1> HTML and CSS in UX Designer/Developer </h1>
            </div>
            <div class="p">
                <p> A UX designer is in charge of a product or service's user experience. It is their job to ensure that the functionality is smooth, accessible, and intuitive to the user's needs and behaviours. </p>
            </div>
            <div class="photo">
                <img src="pic.jpg" Pic.JPG" width="130" height="145" alt="">
            </div>
            <div class="hrstyle">
                <hr>
            </div>
            <div class="author">
                <p><b> NITHISH R </b></p>
            </div>
            <div class="publisher">
                <b> SEC </b>
            </div>
            <div class="edition">
                <b> Third Edition </b>
            </div>
        </div>
    </body>
</html>
```


## OUTPUT:
![Alt text](<Screenshot (22).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
