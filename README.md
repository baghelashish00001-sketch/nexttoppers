<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Next Toppers</title>

<link rel="stylesheet" href="style.css">

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
</head>

<body>

<header>
<div class="logo">
<h2>Next Toppers</h2>
</div>

<nav>
<ul>
<li><a href="#home">Home</a></li>
<li><a href="#courses">Courses</a></li>
<li><a href="#about">About</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>

<a href="#" class="btn">Enroll Now</a>

</header>

<section class="hero" id="home">

<div class="hero-text">

<h1>Welcome to <span>Next Toppers</span></h1>

<p>
India's Smart Coaching Platform for Class 9-12,
JEE, NEET and Competitive Exams.
</p>

<a href="#" class="hero-btn">Start Learning</a>

</div>

</section>

<section class="courses" id="courses">

<h2>Popular Courses</h2>

<div class="course-container">

<div class="card">
<h3>Class 9-10</h3>
<p>Complete Foundation Program.</p>
</div>

<div class="card">
<h3>Class 11-12</h3>
<p>CBSE & State Board Preparation.</p>
</div>

<div class="card">
<h3>JEE</h3>
<p>Advanced Preparation with Mock Tests.</p>
</div>

<div class="card">
<h3>NEET</h3>
<p>Biology, Physics and Chemistry.</p>
</div>

</div>

</section>

<section class="about" id="about">

<h2>Why Choose Next Toppers?</h2>

<div class="features">

<div>
<h3>Expert Teachers</h3>
<p>Experienced faculty from top institutes.</p>
</div>

<div>
<h3>Live Classes</h3>
<p>Interactive online sessions.</p>
</div>

<div>
<h3>Test Series</h3>
<p>Weekly mock exams with analysis.</p>
</div>

<div>
<h3>Study Material</h3>
<p>Notes, PDFs and Recorded Lectures.</p>
</div>

</div>

</section>

<section class="contact" id="contact">

<h2>Contact Us</h2>

<form>

<input type="text" placeholder="Your Name">

<input type="email" placeholder="Your Email">

<textarea placeholder="Your Message"></textarea>

<button>Send Message</button>

</form>

</section>

<footer>

<p>© 2026 Next Toppers | All Rights Reserved.</p>

</footer>

<script src="script.js"></script>

</body>
</html>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Poppins,sans-serif;
scroll-behavior:smooth;
}

body{
background:#f4f7ff;
color:#333;
}

header{

display:flex;
justify-content:space-between;
align-items:center;
padding:20px 10%;
background:#0B5ED7;
color:white;
position:sticky;
top:0;
}

nav ul{
display:flex;
list-style:none;
}

nav ul li{
margin-left:25px;
}

nav a{
text-decoration:none;
color:white;
font-weight:600;
}

.logo{
font-size:24px;
font-weight:bold;
}

.btn{
background:white;
padding:10px 20px;
color:#0B5ED7;
border-radius:5px;
text-decoration:none;
font-weight:bold;
}

.hero{
height:90vh;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
background:linear-gradient(135deg,#0B5ED7,#6EA8FE);
color:white;
}

.hero h1{
font-size:60px;
}

.hero span{
color:yellow;
}

.hero p{
margin:20px;
font-size:20px;
}

.hero-btn{
display:inline-block;
padding:15px 35px;
background:white;
color:#0B5ED7;
font-weight:bold;
text-decoration:none;
border-radius:30px;
}

.courses{
padding:80px 10%;
text-align:center;
}

.course-container{

display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
margin-top:40px;

}

.card{
background:white;
padding:40px;
border-radius:10px;
box-shadow:0 10px 20px rgba(0,0,0,.1);
transition:.3s;
}

.card:hover{
transform:translateY(-10px);
}

.about{
padding:80px 10%;
background:white;
text-align:center;
}

.features{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:30px;
margin-top:40px;
}

.features div{
background:#0B5ED7;
padding:30px;
color:white;
border-radius:10px;
}

.contact{
padding:80px 10%;
text-align:center;
}

form{
max-width:600px;
margin:auto;
}

input,textarea{

width:100%;
padding:15px;
margin:15px 0;
border:1px solid #ddd;
border-radius:5px;

}

button{

padding:15px 35px;
background:#0B5ED7;
color:white;
border:none;
border-radius:5px;
font-size:16px;
cursor:pointer;

}

footer{
background:#111;
color:white;
text-align:center;
padding:25px;
}
