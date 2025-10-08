# Ex.06 Book Front Cover Page Design
## Date:8.10.2025

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
book.html
   <!DOCTYPE html>
<html>
<head>
<title>Book Cover Page</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<div class="cover">
<div class="border">
<h3 class="top">SEC Insights</h3>
<h1>Web Development with node<br>and express</h1>
<p class="sub"> Ideal if you want to learn how to built server-side app </p>
<div class="left">
<h4>SPECIAL EDITION</h4>
<div class="name">
<p>k.vishwathini(25016664)</p>
<div class="right">
<img src="vishwa.jpg "alt="vishwathini Photo">
<hr class="line">
<div class>
<p>SEC</p>
</div>
</div>
</div>
</div>
</div>
</div>
</body>
</html>
style.css
body{
    background-color:beige;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}
 
.cover{
    width: 400px;
    height: 550px;
    background: url(background.jpg);
    background-size:cover;
    background-position: center;
    position: relative;
    text-align: center;
    color: cyan;
    font-family: 'Times New Roman'sans-serif;
    box-shadow:10px  greenyellow;
}

.border{
    border: 4px solid lightseagreen;
    margin: 25px;
    height: 85%;
    padding: 15px;
    position: relative;
}

.insights{
    color: red;
    font-size: 18px;
    font-weight: bold;
    margin-bottom: 10px;
}

h1{
    font-size: 24px;
    margin-top: 30px;
    font-weight: bold;
}

.sub{
    font-style:italic;
    font-size: 15px;
    margin-top: 20px;
}

.left h4{
    position:relative;
    top:200px;
    right: 105px;
    font-size: 15px;
    font-style: unset;
    font-weight: bold;
    margin: 0;
}

.left p{
    position: relative;
    top:195px;
    right:100px;
    font-size: 11px;
}

.right img{
    position: relative;
    top:5px;
    left:90px;
    width: 130px;
    height:150px;
    border: 2px steelblue;
}

.line{
    width:300px;
    background-color: beige;
    height: 2px;
    left: 5px;
    right:opx;
}

.right p{
    font-style: initial;
    font-size: larger;
    top:-7px;
    left: 150px;
    margin-top: 5px;
    font-weight: bold;
}

```

## OUTPUT:
![alt text](<Screenshot (64).png>)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
