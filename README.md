# Ex-06-Book-Cover-Design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps: 

### Step 1:
clone the Github repository and create a Django admin interface.

### Step 2:
Write HTML and CSS Code for designing book cover page and execute them.
## Code:
```
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            background-color: #3d3a3a;
            color:red;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/images/back.png);
            background-size: cover;
        }
            

        .toptext{
            color:red;

        }

        
        .tophr{
            width:140px;
        }
        .author{
            color: red;
            display: inline;
            position: relative;
            color:red;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .publisher{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .edition{
            color:red;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
        }
        .photo{
            position: relative;
            top: 135px;
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
            <div class="toptext">
                SEC INSIGHT
            </div>
            <div class="tophr">
                <hr style="color: red;">
            </div>
            <div class="booktitle">
                <h1>Fundamentals of Web Application Development</h1></div>
            <div class="subtitle">
                HTML and CSS Combined with Django Architecture
            </div>
            <div class="photo">
                <img src="/static/images/my.jpg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: orange;">
            </div>
            <div class="author">
               <p><b>Tamizharasi</b></p>
            </div>
            <div class="publisher">
                SEC
            </div>
            <div class="edition">
                <b>Seventh Edition</b>
            </div>
            
        </div>
    </body>
</html>
```
## Output:

![out](https://user-images.githubusercontent.com/119657317/216114205-9138265f-ed17-497a-b310-f669270a7395.png)


## HTML Validator

![valid (2)](https://user-images.githubusercontent.com/119657317/216111324-4975fc13-594d-4db2-926e-fbb0d2578288.png)

## Result:
The program for designing book cover page using HTML and CSS is executed successfully
