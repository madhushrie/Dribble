# Project Responsive Web Design using Bootstrap
## Date:2.1.2025

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
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">

       <div class="container">
            <a class="navbar-brand" href="#">Dribbble</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#">Explore</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Comments</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Updates</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">New</a></li>
                    <li class="nav-item"><a class="btn btn-dark" href="#">Log in</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="text-center py-5">
        <div class="container">
            <h1 class="display-4">ART AND CRAFT</h1>
            <p class="lead">The Art of Making, The Joy of Creating</p>
            <div class="input-group mb-3">
                <input type="text" class="form-control" placeholder="Explore">
                <button class="btn btn-primary" type="button">Browse</button>
            </div>
        </div>
    </section>

    <!-- Designer Grid -->
    <section class="py-5">
        <div class="container">
            <div class="row g-4">
                <div class="col-md-4">
                    <div class="card">
                        <img src="craft1.jpg" class="card-img-top" alt="craft1">
                        <div class="card-body">
                            <p>Handmade Dolls</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="craft2.png" class="card-img-top" alt="craft2">
                        <div class="card-body">
                            <p>Multan's Handicrafts</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="craft3.jpg" class="card-img-top" alt="craft3">
                        <div class="card-body">
                          <p>DIY Pan\intings</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
<footer class="bg-light py-4">
        <div class="container text-center">
            <p class="mb-0 text-muted">&copy; 2024 Designed and Developed by MADHU SHRIE J</p>
        </div>
    </footer>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    
</body>
</html>
```

## OUTPUT:
![alt text](<madhu/softapp/static/Screenshot (57).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
