# Hi-new-site-
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Shubham | Personal Website</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:linear-gradient(135deg,#4facfe,#00f2fe);
    color:#fff;
}

header{
    text-align:center;
    padding:80px 20px;
}

header h1{
    font-size:55px;
}

header p{
    font-size:22px;
    margin-top:10px;
}

section{
    max-width:900px;
    margin:40px auto;
    background:rgba(255,255,255,0.12);
    padding:30px;
    border-radius:15px;
    backdrop-filter:blur(8px);
}

h2{
    margin-bottom:15px;
}

.skills span{
    display:inline-block;
    background:#fff;
    color:#333;
    padding:10px 18px;
    border-radius:25px;
    margin:8px;
    font-weight:bold;
}

footer{
    text-align:center;
    padding:20px;
    margin-top:40px;
}
button{
    margin-top:20px;
    padding:12px 25px;
    border:none;
    border-radius:30px;
    background:#fff;
    color:#0077ff;
    font-size:18px;
    cursor:pointer;
    font-weight:bold;
}
button:hover{
    background:#222;
    color:white;
}
</style>
</head>

<body>

<header>
    <h1>Hi, I'm Shubham 👋</h1>
    <p>Welcome to My Personal Website</p>

    <button onclick="showMessage()">Say Hello</button>
</header>

<section>
    <h2>About Me</h2>
    <p>
        Hello! My name is <strong>Shubham</strong>.
        This is my personal website where I can share my work,
        achievements, and contact information.
    </p>
</section>

<section>
    <h2>Skills</h2>

    <div class="skills">
        <span>HTML</span>
        <span>CSS</span>
        <span>JavaScript</span>
        <span>Web Design</span>
    </div>

</section>

<section>
    <h2>Contact</h2>

    <p>Email: your@email.com</p>
    <p>Phone: +91-XXXXXXXXXX</p>

</section>

<footer>
    © 2026 Shubham | All Rights Reserved
</footer>

<script>
function showMessage(){
    alert("Welcome to Shubham's Website!");
}
</script>

</body>
</html>
