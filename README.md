<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Talentum Network Consulting</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: 'Poppins', sans-serif;
    }

    body {
        line-height: 1.6;
        color: #333;
        background: #f8f9fc;
    }

    header {
        background: #0d1b2a;
        color: white;
        padding: 20px 10%;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    header h1 {
        font-size: 20px;
        font-weight: 600;
    }

    nav a {
        color: white;
        text-decoration: none;
        margin-left: 20px;
        font-size: 14px;
    }

    .hero {
        background: linear-gradient(to right, #0d1b2a, #1b263b);
        color: white;
        padding: 80px 10%;
        text-align: center;
    }

    .hero h2 {
        font-size: 36px;
        margin-bottom: 20px;
    }

    .hero p {
        max-width: 600px;
        margin: auto;
        font-weight: 300;
    }

    .btn {
        display: inline-block;
        margin-top: 30px;
        padding: 12px 25px;
        background: #fca311;
        color: #000;
        text-decoration: none;
        border-radius: 5px;
        font-weight: 600;
    }

    section {
        padding: 60px 10%;
        text-align: center;
    }

    .services {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 30px;
        margin-top: 40px;
    }

    .card {
        background: white;
        padding: 30px;
        border-radius: 10px;
        box-shadow: 0 5px 15px rgba(0,0,0,0.05);
    }

    .card h3 {
        margin-bottom: 15px;
        font-size: 18px;
    }

    footer {
        background: #0d1b2a;
        color: white;
        text-align: center;
        padding: 20px;
        font-size: 14px;
    }

    .contact {
        background: #edf2f7;
    }

    input, textarea {
        width: 100%;
        padding: 10px;
        margin-top: 10px;
        border: 1px solid #ccc;
        border-radius: 5px;
    }

    form {
        max-width: 500px;
        margin: 30px auto 0;
    }
</style>
</head>
<body>

<header>
    <h1>Talentum Network Consulting</h1>
    <nav>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero">
    <h2>Hiring Partners for Growing Organisations</h2>
    <p>Specialists in Mid-Level to Senior Leadership Hiring across IT and Non-IT sectors. We deliver quality talent through ownership, speed, and accountability.</p>
    <a href="#contact" class="btn">Partner With Us</a>
</section>

<section id="about">
    <h2>About Us</h2>
    <p style="max-width:700px; margin:20px auto;">
        Talentum Network Consulting is a recruitment and executive search firm focused on partnering with growth-driven organisations. 
        With strong business understanding and deep market insights, we focus on quality fitment rather than just profile closures.
    </p>
</section>

<section id="services">
    <h2>Our Services</h2>
    <div class="services">
        <div class="card">
            <h3>Mid-Level Hiring</h3>
            <p>Strategic hiring support for managers and functional leaders across industries.</p>
        </div>
        <div class="card">
            <h3>Leadership Search</h3>
            <p>Executive search for senior and CXO-level roles with focused market mapping.</p>
        </div>
        <div class="card">
            <h3>IT & Non-IT Recruitment</h3>
            <p>Comprehensive talent solutions across technology and diversified business sectors.</p>
        </div>
    </div>
</section>

<section id="contact" class="contact">
    <h2>Contact Us</h2>
    <form>
        <input type="text" placeholder="Your Name" required>
        <input type="email" placeholder="Your Email" required>
        <textarea rows="5" placeholder="Your Message"></textarea>
        <button class="btn" type="submit">Submit</button>
    </form>
</section>

<footer>
    © 2026 Talentum Network Consulting | All Rights Reserved
</footer>

</body>
</html>
