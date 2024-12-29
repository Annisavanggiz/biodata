<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile Biodata</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 15px;
            text-align: center;
        }
        nav {
            background-color: #333;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .section-hero {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 20px;
            background-color: #f9f9f9;
        }
        .section-hero h1 {
            margin: 0;
        }
        .section-hero img {
            max-width: 300px;
            height: auto;
            border-radius: 8px;
        }
        .section-biodata {
            padding: 20px;
            background-color: #f1f1f1;
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
        }
        .biodata-box {
            background-color: white;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .section-portfolio {
            padding: 20px;
            background-color: #ffffff;
        }
        .portfolio-item {
            background-color: #f9f9f9;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 8px;
            margin-bottom: 15px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Profile</h1>
    </header>
    <nav>
        <a href="#">Home</a>
        <a href="#about">About</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Contact</a>
    </nav>
    <section class="section-hero">
        <div>
            <h1>John Doe</h1>
            <p>Web Developer | Designer | Content Creator</p>
        </div>
        <img src="profile-picture.jpg" alt="Profile Picture">
    </section>
    <section class="section-biodata">
        <div class="biodata-box">
            <h3>Full Name</h3>
            <p>John Doe</p>
        </div>
        <div class="biodata-box">
            <h3>Age</h3>
            <p>30</p>
        </div>
        <div class="biodata-box">
            <h3>Location</h3>
            <p>New York, USA</p>
        </div>
        <div class="biodata-box">
            <h3>Profession</h3>
            <p>Web Developer</p>
        </div>
        <div class="biodata-box">
            <h3>Hobbies</h3>
            <p>Photography, Traveling</p>
        </div>
        <div class="biodata-box">
            <h3>Contact</h3>
            <p>john.doe@example.com</p>
        </div>
    </section>
    <section class="section-portfolio" id="portfolio">
        <h2>Portfolio</h2>
        <div class="portfolio-item">
            <h3>Project 1</h3>
            <p>Description of project 1.</p>
        </div>
        <div class="portfolio-item">
            <h3>Project 2</h3>
            <p>Description of project 2.</p>
        </div>
        <div class="portfolio-item">
            <h3>Project 3</h3>
            <p>Description of project 3.</p>
        </div>
    </section>
</body>
</html>
