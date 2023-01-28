# Book CoverPage Design

## AIM:

To design a static web site for a book cover page.

## DESIGN STEPS:

## Step 1:
Clone the github repository and create a django admin interface

## Step 2:
Write HTML and CSS for designing book cover page and execute them .

## Step 3:
Validate the HTML and CSS code.

## Step 4:
Publish the website in the given URL.



## PROGRAM :
```
<!DOCTYPE html>
{% load static %}
<html lang="en">
<head>
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>coverpage</title>
<link rel="stylesheet" href="cover.css">
<style>
main{
background-color: rgb(58, 54, 54);
background-image: url('book.jpg');
height: 1000px;
width:800px;
margin-left: 500px;
}
</style>
</head>
<body style="background-color: cadetblue2;">
<main>
<h04000>EXPERT INSIGHT</h4>
<hr id="start" color="orange">
<h1>
Responsive Web <br>
Design with <br>
HTML5 and CSS
</h1>
<p>Develop future-proof responsive websites <br>
using the latest HTML5 and CSS techniques</p>
<p id="edision">THIRD EDISION</p>
<hr id="aj" color="orange">
<img src="ben.png" alt="sdfgh">
<p id="author">Ben Frain</p>
<p id="packt"> <u> Packt> </u></p>
</main>
</body>
</html>>
```
## CSS
```
h4{
    color: rgb(10, 9, 9);
    font-style: sans-serif ;
    padding-left: 60px;
    padding-top: 40px;
    font-family:monospace;
    font-size: 30px;
}
#start{
    margin-right:400px;
}
h1{
    padding-left: 60px;
    color: rgb(0, 0, 0);
    font-size: 70px;
    font-family: sans-serif;
    
}
p{
    padding-left: 60px;
    padding-right: 10px;
    color: rgb(0, 0, 0);
    font-size: 25px;
    font-family: Arial, Helvetica, sans-serif;

}
#edision{
    color: orange;
    font-size: 30px;
    top: 300px;
    display:inline;
    position:relative;
}
#author{
    color:rgb(0, 0, 0);
    font-family:Arial, Helvetica, sans-serif;
    display:inline;
    position:relative;
    font-size:40px;
    font-weight:bold;
    bottom: 150px;
    right: 200px;
}
#packt{
    color: rgb(0, 0, 0);
    font-family:Arial, Helvetica, sans-serif;
    display:inline;
    position:relative;
    left: 40px;
    bottom: 150px;
    font-size:50px;
    font-weight:bold;
}
img{
    display:inline;
    position:relative;
    left: 550px;
    bottom: 210px;

}
#aj{
    margin-top:300px ;
}
```
## OUTPUT:

![Screenshot (181)](https://user-images.githubusercontent.com/118343998/215248533-7b5f6dcd-c4ba-4bb1-9abb-b9224aebea34.png)

## Result:
Thus the experiment was executed successfully.

