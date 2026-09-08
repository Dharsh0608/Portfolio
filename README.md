# Ex01 Portfolio
## Date: 20.07.2026

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
index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dharshana Abirami | Portfolio</title>

    <link rel="stylesheet" href="style.css">

    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
</head>

<body>

    <header>

        <nav>

            <h2 class="logo">Portfolio</h2>

            <ul>

                <li><a href="#">Home</a></li>

                <li><a href="#">About</a></li>

                <li><a href="#">Projects</a></li>

                <li><a href="#">Contact</a></li>

            </ul>

        </nav>

    </header>



    <section class="hero">

        <div class="content">

            <h3>Hello, I'm</h3>

            <h1>Dharshana A S</h1>

            <h2>Information Technology Student</h2>

            <p>
                Passionate about UI/UX Design, Web Development,
                and creating modern digital experiences.
            </p>

            <div class="buttons">

                <a href="#" class="btn">Download Resume</a>

                <a href="#" class="btn btn2">Contact Me</a>

            </div>

        </div>



        <div class="image">

            <img src="image.png" alt="Profile Picture">

        </div>

    </section>

</body>
</html>
```
style.css
```
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

body{

    background:linear-gradient(135deg,#0f172a,#1e3a8a,#2563eb);

    color:white;

}

/* Navigation */

nav{

    display:flex;

    justify-content:space-between;

    align-items:center;

    padding:25px 10%;

}

.logo{

    font-size:30px;

    font-weight:bold;

}

nav ul{

    display:flex;

    list-style:none;

}

nav ul li{

    margin-left:35px;

}

nav ul li a{

    color:white;

    text-decoration:none;

    transition:.3s;

}

nav ul li a:hover{

    color:#60a5fa;

}


/* Hero */

.hero{

    height:90vh;

    display:flex;

    align-items:center;

    justify-content:space-between;

    padding:0 10%;

}

/* Text */

.content{

    max-width:550px;

}

.content h3{

    font-size:30px;

}

.content h1{

    font-size:65px;

    margin:10px 0;

}

.content h2{

    color:#93c5fd;

    margin-bottom:20px;

}

.content p{

    line-height:1.8;

    color:#dbeafe;

    margin-bottom:35px;

}

/* Buttons */

.btn{

    text-decoration:none;

    background:#2563eb;

    color:white;

    padding:14px 28px;

    border-radius:30px;

    margin-right:15px;

    transition:.3s;

}

.btn:hover{

    background:white;

    color:#2563eb;

}

.btn2{

    background:transparent;

    border:2px solid white;

}

/* Image */

.image img{

    width:380px;

    height:380px;

    border-radius:50%;

    object-fit:cover;

    border:8px solid white;

    box-shadow:0 0 35px rgba(255,255,255,.35);

}

/* Responsive */

@media(max-width:900px){

.hero{

flex-direction:column-reverse;

text-align:center;

margin-top:40px;

}

.image img{

width:260px;

height:260px;

margin-bottom:40px;

}

.content h1{

font-size:45px;

}

nav{

flex-direction:column;

}

nav ul{

margin-top:20px;

}

}
```

## OUTPUT
![alt text](image-1.png)


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
