#Ex 01:protofolio
## Date:

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
## index.html
DOCTYPE html>
<html>
<head>
<title>Dharani Portfolio</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<div class="portfolio">

<div class="left">

<img src="oharani.jpeg" class="photo">

<h1>DHARANI</h1>

<h3>Computer Science Engineering Student</h3>

</div>

<div class="right">

<h2>ABOUT ME</h2>

<p>
Passionate about Web Development, Blockchain,
Python, SQL and creating innovative projects.
</p>

<h2>SKILLS</h2>

<div class="skill">HTML</div>
<div class="skill">CSS</div>
<div class="skill">Python</div>
<div class="skill">SQL</div>
<div class="skill">Blockchain</div>

<h2>PROJECTS</h2>

<ul>
<li>Healthcare Record Management</li>
<li>Customer Segmentation</li>
</ul>

<h2>CONTACT</h2>

<p>📧 dharaniammu143kd@gmail.com</p>
<p>📱 +91 9344402783</p>

</div>

</div>

</body>
</html>

## style.css
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,Helvetica,sans-serif;
}

body{
height:100vh;
display:flex;
justify-content:center;
align-items:center;
background:linear-gradient(135deg,#0f2027,#203a43,#2c5364);
overflow:hidden;
}

.portfolio{

width:95%;
height:92vh;

display:flex;

border:8px solid white;

border-radius:30px;

background:white;

box-shadow:0 0 40px cyan;

}

.left{

width:35%;

background:#0d6efd;

color:white;

display:flex;

flex-direction:column;

justify-content:center;

align-items:center;

padding:20px;

border-right:8px solid white;

}

.photo{

width:250px;

height:250px;

border-radius:50%;

border:8px solid white;

object-fit:cover;

box-shadow:0 0 30px white;

margin-bottom:30px;

}

.left h1{

font-size:42px;

margin-bottom:15px;

letter-spacing:3px;

}

.left h3{

text-align:center;

}

.right{

width:65%;

padding:40px;

}

.right h2{

margin-top:20px;

margin-bottom:15px;

font-size:30px;

border-left:8px solid #0d6efd;

padding-left:15px;

color:#0d6efd;

}

.right p,.right li{

font-size:20px;

line-height:35px;

}

.skill{

display:inline-block;

padding:12px 22px;

background:#0d6efd;

color:white;

margin:8px;

border-radius:30px;

font-weight:bold;

font-size:18px;

}

.skill:hover{

background:#222;

transform:scale(1.1);

transition:.3s;

cursor:pointer;

}

ul{

margin-left:30px;

}

@media(max-width:900px){

.portfolio{

flex-direction:column;

height:auto;

overflow:auto;

}

.left,.right{

width:100%;

}

body{

overflow:auto;

}

}

## OUTPUT
<img width="1881" height="906" alt="Screenshot 2026-07-26 202158" src="https://github.com/user-attachments/assets/5a051b60-d8b9-42b4-b8ca-8a0aab7b88f4" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
