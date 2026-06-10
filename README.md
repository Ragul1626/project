# Project Responsive Web Design using Bootstrap
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
# Dribble.html:
```
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <nav class="navbar navbar-expand-lg" style="background-color: rgb(219, 124, 140);">
        <div class="container">
            <a class="navbar-brand" href="#">Dribbble</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#shots">Shots</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <div class="bg-light text-center py-5">
        <div class="container">
            <h1 class="display-4">Discover the World of Design</h1>
            <p class="lead">Explore amazing shots from creative professionals all around the world.</p>
            <a href="#shots" class="btn btn-primary">View Shots</a>
        </div>
    </div>

    <div id="shots" class="container my-5">
        <h2 class="text-center mb-4">Featured Shots</h2>
        <div class="row row-cols-1 row-cols-md-3 g-4">
            <div class="col">
                <div class="card">
                    <img src="project 1.webp" class="card-img-top" alt="Shot 1">
                    <div class="card-body">
                        <h5 class="card-title">LOGO MAKER</h5>
                        <p class="card-text">Obsessed with this show.
                        Visit my Instagram to see the full process</p>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card">
                    <img src="project 2.webp" class="card-img-top" alt="Shot 2">
                    <div class="card-body">
                        <h5 class="card-title">APP DESIGN</h5>
                        <p class="card-text">22+ Categories, New screens added weekly, lifetime updates
                        (for Designers and Startups).</p>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card">
                    <img src="project 3.webp" class="card-img-top" alt="Shot 3">
                    <div class="card-body">
                        <h5 class="card-title">Finance web design</h5>
                        <p class="card-text">Luxury Elegant Modern Fireplace Furniture Website Responsive</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div id="about" class="bg-light py-5">
        <div class="container">
            <h2 class="text-center mb-4">About Us</h2>
            <p class="text-center">Dribbble is the go-to platform for discovering and showcasing creative work. We empower designers and artists to share their projects, connect with others, and find inspiration.</p>
        </div>
    </div>

    <footer class="bg-dark text-white py-4">
        <div class="container text-center">
            <p>&copy; 2025 Dribbble Clone. All rights reserved.Designed and Developed by ragul m</p>
        </div>
    </footer>
  
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
# OUTPUT:

![Screenshot 2025-05-26 111412](https://github.com/user-attachments/assets/a2db1577-9f7a-419e-a436-7506295ae804)

# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
