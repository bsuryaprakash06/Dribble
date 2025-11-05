# Project Responsive Web Design using Bootstrap
## Date: 05-11-2025

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Design a navigation bar with links: Inspiration, Find Work, Learn Design, Go Pro, Sign In, Sign Up.

### Step 5:
Add a catchy headline with a search bar.

### Step 6:
Use ```<div>``` containers for each dribbble shot thumbnail.

### Step 7:
Include designer name and likes count below each image.

### Step 8:
Include text like “Find your next design inspiration” with a button (“Join Dribbble” or “Explore”).

### Step 9:
Create a footer with your name and register number.

### Step 10:
Publish the website in the LocalHost.

## PROGRAM :

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone - Shane</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>

    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark shadow-sm sticky-top">
        <div class="container">
            <a class="navbar-brand fw-bold text-white" href="#">Dribbble Clone</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navMenu">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse" id="navMenu">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link text-white" href="#">Inspiration</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#">Find Work</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#">Learn Design</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#">Go Pro</a></li>
                </ul>
            </div>
        </div>
    </nav>


    <!-- Hero Section -->
    <section class="py-5 text-center bg-light">
        <div class="container">
            <div class="row justify-content-center align-items-center">
                <div class="col-lg-8">
                    <h1 class="fw-bold mb-3">Discover the world’s top designers</h1>
                    <p class="lead mb-4">Explore thousands of amazing design shots and creative works from
                        professionals.</p>
                    <button class="btn btn-dark btn-lg mb-4">Explore Now</button>
                    <div class="container my-5">
                        <div class="row justify-content-center text-center">

                            <div class="col-lg-4 col-md-6 mb-4 d-flex justify-content-center">
                                <img src="https://images.unsplash.com/photo-1506765515384-028b60a970df?auto=format&fit=crop&w=800&q=80"
                                    class="img-fluid rounded shadow" alt="Design 1" style="max-width: 80%;">
                            </div>

                            <div class="col-lg-4 col-md-6 mb-4 d-flex justify-content-center">
                                <img src="https://images.unsplash.com/photo-1658863025658-4a259cc68fc9?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&q=80&w=1325"
                                    class="img-fluid rounded shadow" alt="Design 2" style="max-width: 80%;">
                            </div>

                            <div class="col-lg-4 col-md-6 mb-4 d-flex justify-content-center">
                                <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?auto=format&fit=crop&w=800&q=80"
                                    class="img-fluid rounded shadow" alt="Design 3" style="max-width: 80%;">
                            </div>

                        </div>
                    </div>

                </div>
            </div>
        </div>
    </section>

    <!-- Content Section -->
    <section class="py-5">
        <div class="container text-center">
            <h2 class="mb-5 fw-semibold">Featured Shots</h2>
            <div class="row g-4 justify-content-center">

                <div class="col-md-4 col-sm-6">
                    <div class="card border-0 shadow-sm h-100">
                        <img src="https://images.unsplash.com/photo-1558655146-d09347e92766?ixlib=rb-4.1.0&auto=format&fit=crop&q=80&w=764"
                            class="card-img-top object-fit-cover" alt="Design 1" style="height: 250px;">
                        <div class="card-body">
                            <h5 class="card-title">Creative UI Concept</h5>
                            <p class="card-text text-muted">Modern dashboard design with clean interface.</p>
                        </div>
                    </div>
                </div>

                <div class="col-md-4 col-sm-6">
                    <div class="card border-0 shadow-sm h-100">
                        <img src="https://images.unsplash.com/photo-1609409601877-b24383c3a5e1?ixlib=rb-4.1.0&auto=format&fit=crop&q=80&w=1470"
                            class="card-img-top object-fit-cover" alt="Design 2" style="height: 250px;">
                        <div class="card-body">
                            <h5 class="card-title">Mobile App Mockup</h5>
                            <p class="card-text text-muted">A sleek and minimal app design for startups.</p>
                        </div>
                    </div>
                </div>

                <div class="col-md-4 col-sm-6">
                    <div class="card border-0 shadow-sm h-100">
                        <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?auto=format&fit=crop&w=800&q=80"
                            class="card-img-top object-fit-cover" alt="Design 3" style="height: 250px;">
                        <div class="card-body">
                            <h5 class="card-title">Product Page Layout</h5>
                            <p class="card-text text-muted">An elegant ecommerce layout for better UX.</p>
                        </div>
                    </div>
                </div>

            </div>
        </div>

    </section>

    <!-- Join Section -->
    <section class="py-5 bg-dark text-white text-center">
        <div class="container">
            <h2 class="fw-bold mb-3">Join our creative community</h2>
            <p class="mb-4">Showcase your work, get feedback, and connect with designers worldwide.</p>
            <button class="btn btn-light btn-lg">Sign Up for Free</button>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-3 bg-light text-center">
        <div class="container">
            <p class="mb-0">© 2025 Shane</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>
```

## OUTPUT:

<img width="1878" height="1119" alt="dribbleClone" src="https://github.com/user-attachments/assets/a2b44af0-cf95-4003-8fc1-0a92291f9209" />

## RESULT:
The project for responsive web design in creating a clone of dribble.com is completed successfully.
