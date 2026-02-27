# Ex01 Portfolio
## Date: 27 02 2026

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

```

<!DOCTYPE html>
<html>
<head>
<title>Sharma R| Portfolio</title>
<style>
body{margin:0;font-family:Arial;background:#f4f4f4;text-align:center;}
nav{background:#111;padding:15px;}
nav a{color:white;margin:0 20px;cursor:pointer;text-decoration:none;}
nav a:hover{color:#00bcd4;}

.page{display:none;padding:50px;}
.active{display:block;}

img{width:140px;height:140px;border-radius:50%;margin-top:20px;}

.card{
  background:white;
  margin:20px auto;
  padding:20px;
  width:80%;
  max-width:600px;
  box-shadow:0 3px 6px rgba(0,0,0,0.1);
}

button{
  padding:8px 15px;
  background:#00bcd4;
  border:none;
  color:white;
  cursor:pointer;
}
button:hover{background:#0097a7;}

.link{
  color:#00bcd4;
  text-decoration:none;
}
.link:hover{ text-decoration:underline; }
</style>
</head>

<body>

<nav>
  <a onclick="show('home')">Home</a>
  <a onclick="show('projects')">Projects</a>
  <a onclick="show('contact')">Contact</a>
</nav>

<!-- HOME -->
<div id="home" class="page active">
  <!-- Put your image in same folder and rename to profile.jpg -->
  <img src="Sharma R 212224230261.jpg">
  <h1>SHARMA R</h1>
  <p>Creative Designer | Front-End Developer</p>

  <div class="card">
    <h3>About Me</h3>
    <p>I build simple and responsive websites using HTML, CSS, JavaScript and React.</p>
    <button onclick="show('projects')">View Projects</button>
  </div>
</div>

<!-- PROJECTS -->
<div id="projects" class="page">
  <h2>My Projects</h2>

  <div class="card">
    <h4>Cartify - E-commerce Website</h4>
    <p>Shopping site with cart feature.</p>
  </div>

  <div class="card">
    <h4>Smart PDF Reader</h4>
    <p>Browser-based PDF reading app.</p>
  </div>

  <div class="card">
    <h4>Drestein '24 Website</h4>
    <p>Workshop event website built with Flutter.</p>
  </div>
</div>

<!-- CONTACT -->
<div id="contact" class="page">
  <h2>Contact Me</h2>

  <div class="card">
    <p>Email: 
      <a href="mailto:rattishkumars@gmail.com" class="link">
        rattishkumars@gmail.com
      </a>
    </p>

    <p>GitHub: 
      <a href="https://github.com/Rattishaids" target="_blank" class="link">
        github.com/Rattishaids
      </a>
    </p>

    <p>LinkedIn: 
      <a href="https://www.linkedin.com/in/rattish-kumar-ss-7881ab276/" 
         target="_blank" class="link">
        linkedin.com/in/rattish-kumar-ss
      </a>
    </p>
  </div>
</div>

<script>
function show(id){
  document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
  document.getElementById(id).classList.add('active');
}
</script>

</body>
</html>

```


## OUTPUT

<img width="1907" height="1074" alt="image" src="https://github.com/user-attachments/assets/5bf8cc5b-6de1-4b6b-a878-11eb32e71cef" />

<img width="1865" height="1080" alt="image" src="https://github.com/user-attachments/assets/44636da5-926f-438d-b4a3-1fe84ff9c808" />




## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
