# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
clone into the repository named "cover-page-design" and do the necessary changes in 
settings.py 
### Step 2:
create a file 'cover.html' and write down the cover page code required.

### step 3:
Runserver to get the output.

## Code:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta name="viewport"
        content="width=device-width,initial-scale=1.0">
        <style>
        
        .bookpage{
          width: 400px;
          height: 600px;

          color:red;
          margin-left: auto;
          margin-right: auto;
          padding: 20px;
          font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
          background-image:url(/static/images/back.jpg);
          background-size: cover;

        }

        .insight{
            color:white;


        }

        .hrstyle{
            width: 30px;

        }
        .author{
            color:yellowgreen;
            display: inline;
            position: relative;
            color: red;
            top: 190px;


            font-family: Georgia;
            font-size: medium;

        }

        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: large;
            text-align: inherit;
            position: relative;
            top: 30px;

        }
        .id{
            width: 400px;
            position: relative;
            top: 180px;


        }
        .pub{
            font-size: medium;
            position: relative;
            top: 155px;
            left: 330px;
        }
        .ed{
            color:blue;
            font-size: large;
            font-family: Verdana;
            position: relative;
            top: 65px;

        }
        .subtitle{
            font-family: Tahoma;
            font-size: medium;
            position: relative;
            top: 10px;

        }
        .mypic{
            position: relative;
            top: 220px;
            left: 320px;
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
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color:white;">
            </div>
            <div class="booktitle">
                <h1> Fundamentals of Web Application Development </h1></div>
            <div class="subtitle">
                HTML and CSS combined with Django Architecture
            </div>
            <div class="mypic">
                <img src="/static/images/mine.jpeg" width=" 65" height="70"alt="">
            </div>
            <div class="id">
                <hr style="color:red;">
            </div>
            <div class="author">
                <p><b>Dinesh</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Seventh Edition</b>
            </div>


        </div>
    </body>
</html>
```

## Output:
cover page:
![COVER](images/back.jpg)
![COVER](images/mine.jpeg)

## Result:
cover page designed and displayed successfully.
