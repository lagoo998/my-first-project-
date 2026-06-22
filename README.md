<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Personal Account</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: Arial, sans-serif;
}

body{
    background: linear-gradient(135deg,#0f172a,#1e293b,#2563eb);
    color:white;
}

header{
    min-height:100vh;
    display:flex;
    align-items:center;
    justify-content:center;
    padding:40px;
}

.container{
    max-width:1100px;
    width:100%;
    display:flex;
    flex-wrap:wrap;
    gap:40px;
    align-items:center;
    justify-content:center;
}

.profile-image{
    flex:1;
    min-width:300px;
    text-align:center;
}

.profile-image img{
    width:350px;
    max-width:100%;
    border-radius:20px;
    border:5px solid white;
    box-shadow:0 10px 30px rgba(0,0,0,0.4);
}

.content{
    flex:1;
    min-width:300px;
}

.content h1{
    font-size:3rem;
    margin-bottom:10px;
}

.content h3{
    color:#93c5fd;
    margin-bottom:20px;
}

.content p{
    line-height:1.8;
    margin-bottom:20px;
}

.btn{
    display:inline-block;
    padding:12px 25px;
    background:white;
    color:#2563eb;
    text-decoration:none;
    border-radius:30px;
    font-weight:bold;
    transition:0.3s;
}

.btn:hover{
    background:#dbeafe;
}

section{
    padding:60px 10%;
}

.card{
    background:rgba(255,255,255,0.1);
    backdrop-filter:blur(10px);
    border-radius:15px;
    padding:25px;
    margin-top:20px;
}

.details{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

footer{
    text-align:center;
    padding:20px;
    background:rgba(0,0,0,0.2);
}
</style>
</head>

<body>

<header>
<div class="container">

<div class="profile-image">
    <img src="C:\Users\Vostro\Pictures\IMG_20251018_201529.jpg" alt="Profile Picture">
</div>

<div class="content">
    <h1>Lastington Daniel Makuyana </h1>
    <h3>Student | Content Creator | Developer</h3>

    <p>
        Welcome to my personal website. Here you can learn more about me,
        my skills, projects, achievements, and ways to contact me.
    </p>

    <a href="#about" class="btn">Learn More</a>
</div>

</div>
</header>

<section id="about">
    <h2>About Me</h2>

    <div class="card">
        <p>
            I am passionate about technology, creativity, and personal growth.
            I enjoy learning new skills, creating digital content, and building
            projects that solve real-world problems, l like to code a teach people how to code 
        </p>
    </div>
</section>

<section>
    <h2>Personal Details</h2>

    <div class="details">

        <div class="card">
            <h3>Full Name</h3>
            <p>Lastington Daniel Makuyana</p>
        </div>

        <div class="card">
            <h3>Location</h3>
            <p>Zimbabwe</p>
        </div>

        <div class="card">
            <h3>Email</h3>
            <p>makuyanalastingtondaniel@gmail.com</p>
        </div>

        <div class="card">
            <h3>Occupation</h3>
            <p>Student / Entrepreneur</p>
        </div>

    </div>
</section>

<section>
    <h2>Skills</h2>

    <div class="card">
        <ul>
            <li>Web Development</li>
            <li>Graphic Design</li>
            <li>Video Editing</li>
            <li>Content Creation</li>
            <li>Programming</li>
        </ul>
    </div>
</section>

<section>
    <h2>Contact</h2>

    <div class="card">
        <p>Facebook: @MAKUYANA LASTINGTON</p>
        <p>Instagram: @MAKUYANA LASTINGTON</p>
        <p>WhatsApp: +263 780891348</p>
    </div>
</section>
<footer>
    <p>© 2025 Lastington Daniel. All Rights Reserved.</p>
</footer>

</body>
</html>
