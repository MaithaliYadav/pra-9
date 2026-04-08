<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Practical No : 9</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<style>
*{margin:0;padding:0;box-sizing:border-box}
body{font-family:'Poppins',sans-serif}
header{background:linear-gradient(135deg,#4facfe,#00f2fe);color:#fff;text-align:center;padding:60px 20px;animation:fadeIn 2s}
nav{display:flex;justify-content:center;background:#333}
nav a{color:#fff;padding:15px;text-decoration:none;transition:.3s}
nav a:hover{background:#4facfe;transform:scale(1.1)}
.container{display:flex;flex-wrap:wrap;padding:20px}
.sidebar{flex:1;min-width:250px;background:#f4f4f4;padding:20px}
.content{flex:3;min-width:300px;padding:20px}
.multi-column{column-count:3;column-gap:20px}
.card{background:#fff;padding:20px;margin:10px 0;border-radius:10px;box-shadow:0 4px 8px rgba(0,0,0,.1);transition:.3s}
.card:hover{transform:translateY(-10px) scale(1.03)}
.icon{font-size:30px;color:#4facfe;margin-bottom:10px}
button{padding:10px 20px;border:none;background:#4facfe;color:#fff;border-radius:5px;cursor:pointer;transition:.3s}
button:hover{background:#00c6ff;transform:rotate(5deg) scale(1.1)}
footer{text-align:center;padding:20px;background:#333;color:#fff}
@keyframes fadeIn{from{opacity:0;transform:translateY(-20px)}to{opacity:1;transform:translateY(0)}}
@media(max-width:768px){.multi-column{column-count:1}nav{flex-direction:column}}
</style>
</head>

<body>
<header>
<h1>Maithali Yadav</h1>
<p>CSS3 Features Demo</p>
<h2>Section : "C"</h2>
<h3>USN : CS25153</h3>
</header>

<nav>
<a href="#"><i class="fas fa-home"></i> Home</a>
<a href="#"><i class="fas fa-user"></i> About</a>
<a href="#"><i class="fas fa-cog"></i> Services</a>
<a href="#"><i class="fas fa-envelope"></i> Contact</a>
</nav>

<div class="container">
<aside class="sidebar">
<h2>Sidebar</h2>
<p>Responsive sidebar section</p>
<button>Click Me</button>
</aside>

<main class="content">
<h2>Multi-Column Layout</h2>
<div class="multi-column">
<p>CSS3 multi-column layout creates newspaper-style text flow.</p>
<p>Responsive design adapts layout to different screen sizes.</p>
<p>Animations and transformations improve UI experience.</p>
</div>

<h2>Cards</h2>
<div class="card">
<div class="icon"><i class="fas fa-laptop-code"></i></div>
<h3>Web Development</h3>
<p>Modern responsive websites.</p>
</div>

<div class="card">
<div class="icon"><i class="fas fa-mobile-alt"></i></div>
<h3>Mobile Design</h3>
<p>Optimized for all devices.</p>
</div>
</main>
</div>

<footer>
<p>© 2026 Responsive Design</p>
</footer>
</body>
</html>
