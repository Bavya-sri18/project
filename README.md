# Project Responsive Web Design using Bootstrap
# Date:
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
  <title>Elegant Dribbble Clone</title>
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      font-family: 'Arial', sans-serif;
      line-height: 1.6;
    }
    .navbar {
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }
    .hero {
      background: linear-gradient(to right, #000000, #323530);
      color: white;
      padding: 100px 0;
      text-align: center;
    }
    .hero h1 {
      font-size: 3.5rem;
      margin-bottom: 20px;
    }
    .features i {
      font-size: 3rem;
      color: #4e54c8;
    }
    .portfolio img {
      border-radius: 15px;
      transition: transform 0.3s;
    }
    .portfolio img:hover {
      transform: scale(1.05);
    }
    .team img {
      border-radius: 50%;
      transition: transform 0.3s;
    }
    .team img:hover {
      transform: scale(1.1);
    }
    footer {
      background: #241313;
      color: white;
      text-align: center;
      padding: 20px 0;
    }
  </style>
</head>
<body>
  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-white">
    <div class="container">
      <a class="navbar-brand" href="#">Elegant Dribbble</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="#features">Features</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#portfolio">Portfolio</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#team">Team</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="hero">
    <div class="container">
      <h1>Create, Inspire, Share</h1>
      <p class="lead">A place where design and creativity come together</p>
      <a href="#features" class="btn btn-outline-light btn-lg">Explore Now</a>
    </div>
  </section>

  <!-- Features Section -->
  <section id="features" class="py-5 text-center">
    <div class="container">
      <h2 class="mb-4">Why Choose Us?</h2>
      <p class="text-muted mb-5">Explore the unique features that make us the ideal platform for creativity and collaboration.</p>
      <div class="row">
        <div class="col-md-4">
          <i class="bi bi-brush mb-3" style="font-size: 3rem; color: #4e54c8;"></i>
          <h3 class="mt-3">Creative Tools</h3>
          <p>Access top-notch tools to unleash your creativity.</p>
        </div>
        <div class="col-md-4">
          <i class="bi bi-people mb-3" style="font-size: 3rem; color: #4e54c8;"></i>
          <h3 class="mt-3">Global Community</h3>
          <p>Connect with like-minded designers and creators.</p>
        </div>
        <div class="col-md-4">
          <i class="bi bi-lightbulb mb-3" style="font-size: 3rem; color: #4e54c8;"></i>
          <h3 class="mt-3">Inspiration Hub</h3>
          <p>Find endless inspiration to fuel your passion.</p>
        </div>
      </div>
    </div>
  </section>
  

  <!-- Portfolio Section -->
  <section id="portfolio" class="py-5 bg-light">
    <div class="container">
      <h2 class="text-center mb-5">Our Latest Projects</h2>
      <div class="row g-4">
        <div class="col-lg-4 col-md-6">
          <img src="image4.webp" class="img-fluid shadow-sm" alt="Project 1">
        </div>
        <div class="col-lg-4 col-md-6">
          <img src="project 2 image.jpg" class="img-fluid shadow-sm" alt="Project 2">
        </div>
        <div class="col-lg-4 col-md-6">
          <img src="image3.jpg" class="img-fluid shadow-sm" alt="Project 3">
        </div>
      </div>
    </div>
  </section>

  <!-- Team Section -->
  <section id="team" class="py-5">
    <div class="container">
      <h2 class="text-center mb-5">Meet Our Team</h2>
      <div class="row text-center">
        <div class="col-md-4">
          <img src="portrait-adult-male-smiling_23-2148729648.avif" class="img-fluid shadow-sm" alt="Team Member 1">
          <h5 class="mt-3">Alice Brown</h5>
          <p>Lead Designer</p>
        </div>
        <div class="col-md-4">
          <img src="team member2.avif" class="img-fluid shadow-sm" alt="Team Member 2">
          <h5 class="mt-3">John Smith</h5>
          <p>Web Developer</p>
        </div>
        <div class="col-md-4">
          <img src="team member3a.avif" class="img-fluid shadow-sm" alt="Team Member 3">
          <h5 class="mt-3">Emily White</h5>
          <p>Marketing Specialist</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>Designed with ❤️ by Bavya © 2024</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

# OUTPUT:
![Screenshot (95)](https://github.com/user-attachments/assets/9fd2b666-06f5-4566-b7ce-276867e027b1)
![Screenshot (96)](https://github.com/user-attachments/assets/7d3de346-06d6-4c89-806d-9b072a66043b)
![Screenshot (97)](https://github.com/user-attachments/assets/c4fa6887-d097-4e37-80cb-5b726e3c2945)


# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
