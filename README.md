# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Clone the Github Repository and Create the Django admin interface.

### Step 2:
Write HTML and CSS code for designing book cover page and execute them.

## Code:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title> Mein Kampf</title>
        <style>
        h1
        {
           color:white;
        }
         .bookpage
         {
             width: 400px;
             height: 650px;
             background-color: black;
             background-position: center;
             margin-left: auto;
             margin-right: auto ;
             padding: 20px;
             background-image: url('/static/images/pic2.jpg');
             background-size: cover;
             background-repeat: no-repeat;
         }
         .toptext
         {
             color:white;
             padding-left: 10px;
             font-size: 14px;
             font-family: Arial, Helvetica, sans-serif;
         }
         .tophr
         {
             color:#e36f2f;
              width: 180px;
         }
         hr
         {
             color:#e36f2f;
         }
         .booktitle
         {
             font-family: Arial, Helvetica, sans-serif;
             padding: 10px 10px 0px 10px;
             display: flex;
            align-items: center;
            justify-content: center;
  margin-right: 10px;
  margin-left: 10px;
  font-size: 20px;
         }
         .author
         {
             color:white;
             font-family: Arial, Helvetica, sans-serif;
             display: inline;
             font-size: 24px;
             position:relative;
             line-height: 20px;
         }
         .sub-text 
         {
             color:white;
             font-family: Arial, Helvetica, sans-serif;
             display: flex;
             line-height: 5px;
  margin-right: 10px;
  margin-left: 10px;
  font-size: 14px;
  }
.footer 
{
  color:orange;
  padding-top: 180px;
}
.image 
{
    color:white;
             font-family: Arial, Helvetica, sans-serif;
 font-size: 22px;
  margin-right: 20px;
}
.bottomhr 
{
    color:#e36f2f;
              width: 400px;
}
img 
{
    width: 90px;
    height: 100px;
    margin-right: 20px;
    vertical-align: bottom;
}
.edition {
    color:#e36f2f;
             font-family: Arial, Helvetica, sans-serif;
 font-size: 22px;
 line-height:bottom;
}
        </style>
        </head>
            <body>
                <div class="bookpage">
                    <div class="toptext">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;EXPERT INSIGHT</div>
                    <div class="tophr"><hr></div>
               <div class="booktitle"><h1>Mein Kampf</h1></div>
               <h3 class="sub-text">The autobiography of Adolf Hitler</h3>
                    <h3 class="sub-text">written by Adolf Hitler</h3>
                    <div class="footer">
                        <h2 class="edition">&nbsp;&nbsp;First
Edition&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <img src="hitler.jpeg" ></h2>
                        <div class="bottomhr"><hr></div>
                    <div class="author"><h3>&nbsp;&nbsp;Adolf Hitler &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</h3></div>
                </div>
                </div>
            </body>
</html>
```

## Output:
![image](https://github.com/Surendhar6/cover-page-design/assets/118352907/877320fc-b821-4e1f-91c9-4a040124e9c6)

## Result:
The program for designing book cover page using HTMl and CSS is executed successfully.
