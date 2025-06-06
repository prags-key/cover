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
<meta name="veiwport"
content="width=device-width,initial-sacale=1.0">
<style>
.bookpage{
width:400px;
height:600px;
color: white;
margin-left: auto;
margin-right: auto;
padding: 20px;
font-family: 'Franklin Gothic Medium','Arial Narrow',Arial,sans-serief;
background-image: url(b1.jpg);
background-size: cover;
}

.insight{
color:rgb(182, 10, 234);
}

.hrstyle{
width: 100px;
}

.author{
display: inline;
position: relative;
color:rgb(249, 7, 156);
top: 190px;
font-family: Georgia;
font-size: medium;
}


.booktitle{
font-family:'Courier New',Courier,manospace;
color:maroon;
font-size: larger;
text-align: center;
position: relative;
top: 30px;
}

.id{
width:400px;
position: relative;
top:180px;
}

.pub{
font-size:medium;
position: relative;
color:rgb(227, 19, 19);
top:155px;
left:330px;
}

.ed{
color:rgba(3, 7, 11, 0.907);
font-size: medium;
font-family: Verdana;
position:relative;
top:85px;
}

.subtitle{
color:rgb(0, 12, 21);
font-family:Tahoma;
font-size:large;
position: relative;
top: 40px;
}


.mypic{
position:relative;
top:135px;
left:260px;
width:100px;
height:100px;
background-size:cover;
}

</style>
<title>Book Cover Page</title>
</head>
<body>
<div class="bookpage">
<div class="insight">
  SEC INSIGHT
</div>
<div class="booktitle">
<h1>The Everything Web Book</h1></div>
<div class="subtitle">
From Scratch to Expert
</div>
<div class="mypic">
<img src="p1.jpg" width="130" height="145" alt="">
</div>
<div class="id">
<hr style="color:rgb(233, 137, 216);">
</div>
<div class="author">
<p><b>PRAGATHI KUMAR</b></p>
</div>
<div class="pub">
    SEC
</div>
<div class="ed">
<b>Third Edition</b>
</div>
</div>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot (125).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
