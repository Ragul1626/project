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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Design Showcase</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        /* Hero Section */
        .hero {
          background-color: #7088a1;
            background-size: cover;
            background-position: center;
            height: 50vh;
            color: rgb(185, 146, 146);
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
        }

        .hero h1 {
            font-size: 3rem;
            padding: 30px;
        }
        .card img {
            height: 200px;
            object-fit: cover;
        }

        .card-body {
            padding: 1.5rem;
        }

        .card-title {
            font-weight: bold;
        }
        .display-4{
          color: rgb(255, 255, 255);
        }
        .lead{
          color: rgb(255, 255, 255);
        }
        #about {
            background-color: #8999a8;
            padding: 60px 0;
        }

        #about p {
            font-size: 1.2rem;
        }
        #contact {
            padding: 60px 0;
        }

        #contact form input, #contact form textarea {
            font-size: 1rem;
            padding: 10px;
            margin-bottom: 20px;
        }

        #contact form button {
            background-color: #007bff;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
        }

        #contact form button:hover {
            background-color: #0056b3;
        }

        /* Footer */
        footer {
            background-color: #343a40;
            color: white;
            padding: 20px 0;
        }

        footer p {
            margin-bottom: 0;
        }
        .body{
          background-color: rgb(105, 84, 56);
        }
        

        
    </style>
</head>
<body>

    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Design Showcase</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#showcase">Showcase</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    <header class="hero">
        <div class="container">
            <h1 class="display-4">Discover Creative Designs</h1>
            <p class="lead">Browse through the most stunning and innovative design works by creatives worldwide.</p>
            <a href="#showcase" class="btn btn-primary btn-lg">Explore Designs</a>
        </div>
    </header>
    <section id="showcase" class="py-5">
        <div class="container">
            <h2 class="text-center mb-5">Featured Designs</h2>
            <div class="row">
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <img src="modern.jpg" class="card-img-top" alt="Design 1">
                        <div class="card-body">
                            <h5 class="card-title">Modern Branding</h5>
                            <p class="card-text">Explore this modern branding project that highlights minimalist principles.</p>
                            <a href="#" class="btn btn-outline-dark">View Design</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <img src="uiux.avif" class="card-img-top" alt="Design 2">
                        <div class="card-body">
                            <h5 class="card-title">Creative UI/UX</h5>
                            <p class="card-text">This user interface design is a blend of simplicity and creativity.</p>
                            <a href="#" class="btn btn-outline-dark">View Design</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <img src="app.jpg" class="card-img-top" alt="Design 3">
                        <div class="card-body">
                            <h5 class="card-title">App Design</h5>
                            <p class="card-text">A sleek mobile app design featuring intuitive navigation and user engagement.</p>
                            <a href="#" class="btn btn-outline-dark">View Design</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section id="about" class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">About Design Showcase</h2>
            <p class="text-center">Design Showcase is a platform where designers around the globe come together to share their creative works. Discover amazing designs, follow talented designers, and get inspired for your next project.</p>
        </div>
    </section>

    <section id="contact" class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">Contact Us</h2>
            <form>
                <div class="mb-3">
                    <label for="name" class="form-label">Your Name</label>
                    <input type="text" class="form-control" id="name" placeholder="Enter your name">
                </div>
                <div class="mb-3">
                    <label for="email" class="form-label">Your Email</label>
                    <input type="email" class="form-control" id="email" placeholder="Enter your email">
                </div>
                <div class="mb-3">
                    <label for="message" class="form-label">Message</label>
                    <textarea class="form-control" id="message" rows="4" placeholder="Write your message"></textarea>
                </div>
                <button type="submit" class="btn btn-primary">Submit</button>
            </form>
        </div>
    </section>

    <footer class="bg-dark text-white text-center py-3">
        <div class="container">
            <p class="mb-0">&copy; 2024 Design Showcase. All rights reserved.ragulm -212224100048</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
# OUTPUT:
![alt text](<proj/Screenshot 2025-05-11 190746.png>)
![alt text](<proj/Screenshot 2025-05-11 190849.png>)
# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
