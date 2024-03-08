<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-LCytI3/6zrV/9rk7vhhnxRTnGgJveRYNvDxm3NLtE8l9lTUZk2vbKsL1Uc5V6TtG" crossorigin="anonymous">
    <style>
        body {
            background-color: #f8f9fa;
        }
        .navbar {
            background-color: #343a40;
        }
        .navbar-brand, .nav-link {
            color: #ffffff;
        }
        .navbar-brand:hover, .nav-link:hover {
            color: #f8f9fa;
        }
        .container {
            background-color: #ffffff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px 0px rgba(0,0,0,0.1);
        }
        .nav-link {
            display: inline-block;
        }
        li{
            display: inline-block;
            
        }
    </style>
</head>
<body>

    <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">My Portfolio</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
                aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link btn btn-primary" href="#home">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link btn btn-primary" href="#about">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link btn btn-primary" href="#projects">Projects</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <div class="container mt-5" id="home">
        <h2>Home</h2>
        <p>Welcome to my portfolio website.</p>
    </div>

    <div class="container mt-5" id="about">
        <h2>About</h2>
        <p>Greetings! I'm Mbevi Warren, a passionate Python developer dedicated to crafting elegant solutions to real-world problems. With a Bachelor's degree in Computer Science from KCA University, I've devoted myself to mastering the art of software development using Python.

My journey in software engineering began with a fascination for the simplicity and versatility of Python. Over the years, I've had the privilege to work on a wide range of projects, leveraging Python's rich ecosystem to build everything from web applications and data analysis tools to automation scripts and machine learning models.

As a Python developer, I thrive on challenges that push the boundaries of what's possible with code. Whether it's wrangling large datasets, designing scalable backend systems, or building intuitive user interfaces, I take pride in my ability to leverage Python's expressive syntax and powerful libraries to deliver robust solutions.

In addition to my expertise in Python, I'm well-versed in related technologies such as Django, Flask, Pandas, NumPy, and TensorFlow, to name a few. I'm constantly exploring new tools and techniques to stay at the forefront of Python development and deliver innovative solutions to my clients and collaborators.

Outside of coding, you'll often find me exploring nature trails with my trusty Python books in hand, experimenting with new Python libraries in my personal projects, or sharing my passion for Python with fellow enthusiasts through workshops and meetups.

I'm excited about the opportunity to connect with like-minded Python developers, collaborate on exciting projects, and make a meaningful impact through the power of Python. Let's write some beautiful code together!</p>
    </div>

    <div class="container mt-5" id="projects">
        <h2>Projects</h2>
        <p>Here are some of my projects:</p>
        <ul>
            <li>Password Generator:</li>
            <li>calculator</li>
            <li>rock scissor paper</li>
        </ul>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-UZSzXZKhQJ4Zk/HEpqcJz1cX+8fQ8gP7UspE3h4K9W93gVN6EoUhjwRBmX6ofIFx"
        crossorigin="anonymous"></script>
</body>
</html>

