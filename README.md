# Project Responsive Web Design using Bootstrap
## Date:24/12/2024

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
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      font-family: Arial, sans-serif;
    }
    .hero {
      background-color: #f7f7f7;
      padding: 50px 20px;
      text-align: center;
    }
    .hero h1 {
      font-size: 2.5rem;
      font-weight: bold;
    }
    .section {
      padding: 40px 20px;
    }
    .footer {
      background-color: #333;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    .nav-link {
      font-weight: 500;
    }
  </style>
</head>
<body>

  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#">Dribbble Clone</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Portfolio</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="hero">
    <h1>Discover and Share Creative Work</h1>
    <p class="mt-3">Explore amazing designs from top creators around the world.</p>
    <button class="btn btn-primary btn-lg mt-4">Get Started</button>
  </section>

  <!-- Content Section 1 -->
  <section class="section bg-light">
    <div class="container text-center">
      <h2>Top Features</h2>
      <p class="mt-3">Dribbble is where designers share, grow, and find inspiration.</p>
      <div class="row mt-4">
        <div class="col-md-4">
          <h5>Showcase Your Work</h5>
          <p>Share your projects and get feedback.</p>
        </div>
        <div class="col-md-4">
          <h5>Connect with Designers</h5>
          <p>Collaborate with professionals worldwide.</p>
        </div>
        <div class="col-md-4">
          <h5>Discover Inspiration</h5>
          <p>Find designs that spark creativity.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Content Section 2 -->
  <section class="section bg-light">
    <div class="container text-center">
      <h2>Gallery</h2>
      <p class="mt-3">Explore some inspiring designs from our community.</p>
      <div class="row mt-4">
        <div class="col-md-3 col-sm-6 mb-4">
          <img src="tt.png" class="img-fluid rounded" alt="Design 1">
          <p class="mt-2">Design 1</p>
        </div>
        <div class="col-md-3 col-sm-6 mb-4">
          <img src="tt2.png" class="img-fluid rounded" alt="Design 2">
          <p class="mt-2">Design 2</p>
        </div>
        <div class="col-md-3 col-sm-6 mb-4">
          <img src="tt3.png" class="img-fluid rounded" alt="Design 3">
          <p class="mt-2">Design 3</p>
        </div>
        <div class="col-md-3 col-sm-6 mb-4">
          <img src="tt4.png" class="img-fluid rounded" alt="Design 4">
          <p class="mt-2">Design 4</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <p> V Rishon Anand (24900460) 2024 Dribbble Clone. All rights reserved.</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```


## OUTPUT:
![alt text](<Screenshot 2024-12-24 090149.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
