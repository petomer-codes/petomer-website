---
layout: post
title: home page + a bit about me
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Awesome Website</title>
    <style>
        /* Basic styling for the navbar and dropdown */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        /* Navbar container */
        .navbar {
            background-color: #333;
            overflow: hidden;
        }

        /* Navbar links */
        .navbar a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }

        .navbar a:hover {
            background-color: #ddd;
            color: black;
        }

        /* Dropdown container */
        .dropdown {
            float: left;
            overflow: hidden;
        }

        /* Dropdown button */
        .dropdown .dropbtn {
            background-color: #333;
            color: white;
            padding: 14px 20px;
            font-size: 16px;
            border: none;
            cursor: pointer;
        }

        .dropdown:hover .dropbtn {
            background-color: #ddd;
            color: black;
        }

        /* Dropdown content (hidden by default) */
        .dropdown-content {
            display: none;
            position: absolute;
            background-color: #333;
            min-width: 160px;
            z-index: 1;
        }

        /* Links inside the dropdown */
        .dropdown-content a {
            color: white;
            padding: 12px 16px;
            text-decoration: none;
            display: block;
        }

        .dropdown-content a:hover {
            background-color: #ddd;
            color: black;
        }

        /* Show the dropdown content when hovering over the dropdown button */
        .dropdown:hover .dropdown-content {
            display: block;
        }

        /* Add some spacing for content */
        .content {
            padding: 20px;
        }
    </style>
</head>
<body>
    <!-- Navbar -->
    <div class="navbar">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <div class="dropdown">
            <button class="dropbtn">Services</button>
            <div class="dropdown-content">
                <a href="#">Web Design</a>
                <a href="#">Web Development</a>
                <a href="#">SEO</a>
            </div>
        </div>
        <a href="#contact">Contact</a>
    </div>

    <!-- Content Section -->
    <div class="content">
        <h1>Hi -- I'm Paige (she/her) and welcome to my website!</h1>
        <p>I created this website to be a publicly accessible trajectory of my research and personal projects. I'm very excited to have this platform to share my work and life with you.</p>

        <h2>Here's a bit more about me, academically:</h2>
        <ul>
            <li>I am starting my PhD program in Biostatistics this fall at the University of Washington -- I'll have a post soon about my application process.</li>
            <li>I received my Bachelors of Arts in Applied Mathematics and Statistics from Macalester College in 2024. My minors were Anthropology and Community & Global Health. I loved my time at Macalester and in the Twin Cities, MN.</li>
            <li>While at Macalester, I completed an Honors project using causal inference in professional women's soccer data.</li>
            <li>I am currently a research fellow in the Durham-Chapel Hill area, and my research right now uses longitudinal modeling to look at associations between puberty and cancer.</li>
        </ul>

        <h2>A bit about me, personally:</h2>
        <ul>
            <li>I'm actually from the Seattle area in Washington, so I am looking forward to being closer to my parents after 5 years!</li>
            <li>I love reading, running, and resting: my big 3! I have had more free time this past year, so I have challenged myself to picking up books and genres that I normally would not read (i.e. <em>Straight</em> by Dick Francis). In running, I started about 2 years ago after playing soccer all of my life. I'm hoping to run my first half marathon this fall in Seattle! And resting is resting, self-explanatory -- I love my bed!</li>
        </ul>
    </div>
</body>
</html>
