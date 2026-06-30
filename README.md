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
document.querySelector("form").addEventListener("submit", function(e){

e.preventDefault();

alert("Thank you for contacting Next Toppers!");

this.reset();

});
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Next Toppers | Student Dashboard</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Poppins,sans-serif;
}

body{
display:flex;
background:#f4f7fb;
transition:.3s;
}

.sidebar{
width:250px;
background:#0b5ed7;
height:100vh;
color:white;
padding:20px;
position:fixed;
}

.logo{
font-size:28px;
font-weight:bold;
margin-bottom:30px;
}

.sidebar ul{
list-style:none;
}

.sidebar li{
padding:15px;
margin:8px 0;
border-radius:8px;
cursor:pointer;
transition:.3s;
}

.sidebar li:hover{
background:rgba(255,255,255,.2);
}

.main{
margin-left:250px;
width:100%;
padding:30px;
}

.topbar{
display:flex;
justify-content:space-between;
align-items:center;
margin-bottom:30px;
}

button{
padding:10px 18px;
border:none;
background:#0b5ed7;
color:white;
border-radius:6px;
cursor:pointer;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
gap:20px;
}

.card{
background:white;
padding:20px;
border-radius:12px;
box-shadow:0 5px 15px rgba(0,0,0,.08);
}

.card h3{
margin-bottom:15px;
}

.progress{
background:#ddd;
height:10px;
border-radius:20px;
overflow:hidden;
}

.progress div{
height:100%;
background:#0b5ed7;
width:75%;
}

table{
width:100%;
border-collapse:collapse;
}

table td,table th{
padding:10px;
border-bottom:1px solid #ddd;
text-align:left;
}

.notice{
padding:10px;
background:#eaf4ff;
margin:10px 0;
border-left:5px solid #0b5ed7;
}

.dark{
background:#111827;
color:white;
}

.dark .card{
background:#1f2937;
color:white;
}

.dark table td,
.dark table th{
border-color:#333;
}

.dark .notice{
background:#2d3748;
}

@media(max-width:900px){

.sidebar{
width:70px;
}

.sidebar .logo{
font-size:18px;
}

.sidebar li{
font-size:12px;
padding:10px;
}

.main{
margin-left:70px;
}

}

</style>
</head>

<body>

<div class="sidebar">

<div class="logo">
Next Toppers
</div>

<ul>

<li>🏠 Dashboard</li>
<li>📚 My Courses</li>
<li>🎥 Live Classes</li>
<li>📝 Assignments</li>
<li>📄 Notes</li>
<li>📊 Results</li>
<li>💬 Doubts</li>
<li>⚙ Settings</li>

</ul>

</div>

<div class="main">

<div class="topbar">

<div>
<h1>Welcome, Ashish 👋</h1>
<p>Student Dashboard</p>
</div>

<button onclick="darkMode()">
Dark Mode
</button>

</div>

<div class="grid">

<div class="card">

<h3>Student Profile</h3>

<p><b>Name:</b> Ashish Baghel</p>

<p><b>Class:</b> 12</p>

<p><b>Course:</b> JEE Advanced</p>

<p><b>Roll No:</b> NT1025</p>

</div>

<div class="card">

<h3>Course Progress</h3>

<div class="progress">

<div></div>

</div>

<br>

75% Completed

</div>

<div class="card">

<h3>Upcoming Live Class</h3>

Physics

<br><br>

7:00 PM

<br><br>

<button>Join Now</button>

</div>

<div class="card">

<h3>Attendance</h3>

92%

</div>

</div>

<br><br>

<div class="grid">

<div class="card">

<h3>Assignments</h3>

<table>

<tr>

<th>Subject</th>

<th>Status</th>

</tr>

<tr>

<td>Physics</td>

<td>Completed</td>

</tr>

<tr>

<td>Chemistry</td>

<td>Pending</td>

</tr>

<tr>

<td>Maths</td>

<td>Completed</td>

</tr>

</table>

</div>

<div class="card">

<h3>Latest Results</h3>

<table>

<tr>

<th>Test</th>

<th>Marks</th>

</tr>

<tr>

<td>Physics</td>

<td>95/100</td>

</tr>

<tr>

<td>Chemistry</td>

<td>92/100</td>

</tr>

<tr>

<td>Maths</td>

<td>97/100</td>

</tr>

</table>

</div>

</div>

<br>

<div class="card">

<h3>Notifications</h3>

<div class="notice">

Physics Live Class starts today at 7 PM.

</div>

<div class="notice">

New Mathematics Notes Uploaded.

</div>

<div class="notice">

JEE Mock Test available now.

</div>

</div>

</div>

<script>

function darkMode(){

document.body.classList.toggle("dark");

}

</script>

</body>
</html>
