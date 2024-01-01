# Ex.06 Book Front Cover Page Design
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
        <meta name="viewport"
        content="width=device-width, initial-scale=1.0">
        <style>
            .bookpage{
                width: 400px;
                height: 600px;
                color: white;
                margin-left: auto;
                margin-right: auto;
                padding: 50px;
                font-family: cursive;
                background-image: url("hi.jpg");
                background-size: cover;
            }
            .insight{
                color: white;

            }
            .hrstyle{
                width: 110px;
            }
            .author{
                display: inline;
                position: relative;
                color:white;
                top: 290px;

                font-family: Georgia;
                font-size: medium;
            }
            .booktitle{
                font-family: 'Times New Roman', Times, serif;
                font-size: medium;
                text-align: center;
                position: relative;
                top: 30px;

            
            }
            .id{
                width: 400px;
                position: relative;
                top: 291px;

            }
            .pub{
                font-size: medium;
                position: relative;
                top: 300px;
                left: 330px;
            }
            .ed{
                color: white;
                font-size: medium;
                font-family: Verdana;
                position: relative;
                top: 198px;

            }
            .subtitle{
                font-family: 'Tahoma';
                font-size: large;
                position: relative;
                text-align: center;
                top: 40px;
            }
            .mypic{
                position: relative;
                top: 250px;
                left: 260px;
                width: 100px;
                height: 100px;
                background-size: cover;
            }
        </style>
        <title>Book Cover Page</title>

    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
               <mark>SEC INSIGHT</mark>
            </div>
            <div class="hrstyle">
                <hr style="color: rgb(0, 255, 72);">
            </div>
            <div class="booktitle">
                <h1><mark >FIGHTS OF KINGDOM</mark></h1>
            </div>
            <div class="subtitle">
                <mark>with Django and Bootstrap Insights</mark>
            </div>
            <div class="mypic">
                <img src="pic.png" width="130" height="140" alt="">
            </div>
            <div class="id">
                <hr style="color:white;">
            </div>
            <div class="author">
                <p><b><mark>SREEKUMAR S</mark></b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b><mark>Extended Edition</mark></b>
            </div>
        </div>

    </body>
</html>
```


## OUTPUT:
![Screenshot 2024-01-01 161656](https://github.com/guru14789/cover/assets/151705853/5a9878fa-5d2b-4142-8681-04c2a1b60c38)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
