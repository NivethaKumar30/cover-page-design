# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

Step 1:
Requirement collection.

Step 2:
Creating the layout using HTML and CSS.

Step 3:
Updating the sample content.

Step 4:
Choose the appropriate style and color scheme.

Step 5:
Validate the layout in various browsers.

Step 6:
Validate the HTML code.

Step 6:
Publish the website in the given URL.

## Code:
```
<!DOCTYPE html>
<html>
    <head>
        <title>BOOK COVER</title>
        <style>
        h1{
            color:#e36f2f;
        }
         .bookpage{
             width: 450px;
             height: 750px;

             margin-left : auto ;
             margin-right : auto ;
             padding: 20px ;
             background-image : url('/static/images/edited.jpg');
             background-size: cover;
             background-repeat: no-repeat;
         }
         .toptext {
             color:rgb(236, 207, 186);
             padding-left : 5px;
             font-size :14px;
             font-family : Arial, Helvetica, sans-serif;
         }
         .tophr{
             color: azure;
             width:180px;
         }
         hr{
             color:bisque;
         }
         .booktitle{
             font-family: Arial, Helvetica, sans-serif;
             padding: 10px 10px 10px 10px;
             display: flex;
             align-items: center;
             justify-content: center;
             margin-right: 10px;
             margin-left: 10px;
             font-size: 30px;
         }
         .author{
             color:white;
             font-family: Arial, Helvetica, sans-serif;
             display: inline;
              font-size: 24px;
              
             
         }
         .sub-text {
             color:white;
             font-family: Arial, Helvetica, sans-serif;
              display: flex;
             margin-right: 10px;
             margin-left: 10px;
             font-size: 20px;
              }
  
         .footer {
  
              padding-top: 10px;
              padding-bottom: 90px;
            }
        .image {
              color:white;
              font-family: Arial, Helvetica, sans-serif;
              font-size: 22px;
              margin-right: 20px;
            }
         .bottomhr { 
              color:#f8ede7;
              width: 450px;
              height:20px;

            }
        img {
            width: 190px;
             height: 190px;
             margin-right: 50px;
             vertical-align: bottom;
            }
         .edition {
             color:#e36f2f;
             font-family: Arial, Helvetica, sans-serif;
             font-size: 22px;
            line-height: 20px;
            }
        </style>
    </head>
    <body>
        <div class="bookpage">
            <div class="toptext">BEST SELLER</div>
            <div class="tophr"><hr></div>
     

        <div class="booktitle">
            <h1>SHINGEKI NO KYOJIN</h1>
        </div>

        <h3 class="sub-text">THE DAY ..</h3>
        <h3 class="sub-text">WHEN HUMANITY RECEIVED... </h3>
        <h3 class="sub-text">A GRIM REMAINDER ...</h3>

        <div class ="footer">
            <h2 class="edition">THIRD EDITION&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="/static/images/isayama.jfif"  alt="author img"></h2>
            <div class="bottomhr"><hr></div>
            <div class="author"><h3>HAJIME ISAYAMA&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;packt></h3></div>
        </div>
       </div>
    </body>
</html>
```
## Output:

## Result:
Thus the Book Cover Designed successfully
