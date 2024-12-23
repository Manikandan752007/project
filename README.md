# Project Responsive Web Design using Bootstrap
## Date: 23-12-2024

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
## Discover.html
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

  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <a class="navbar-brand" href="#">Dribbble Clone</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="bootstrapex-10.html">Discover</a></li>
          <li class="nav-item"><a class="nav-link" href="discover.html">Projects</a></li>
          <li class="nav-item"><a class="nav-link" href="about.html">About</a></li>
          <li class="nav-item"><a class="nav-link btn btn-primary text-white" href="">Sign Up</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <header class="bg-light py-5 text-center">
    <div class="container">
      <h1>Welcome to Dribbble Clone</h1>
      <p class="lead">Showcase your creative work and discover inspiring designs.</p>
      <a href="#" class="btn btn-primary btn-lg">Get Started</a>
    </div>
  </header>

  <!-- Content Section -->
  <section class="py-5">
    <div class="container">
      <h2 class="text-center mb-4">Explore Shots</h2>
      <div class="row">
        <div class="col-md-4">
          <div class="card">
            <img src="https://th.bing.com/th/id/OIG3.80EN2JPNx7kp5VqoB5kz" class="card-img-top" alt="Design 1">
            <div class="card-body">
              <h5 class="card-title">Design 1</h5>
              <p class="card-text">A creative shot to inspire.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS-C_UAhXq9GfuGO452EEzfbKnh1viQB9EDBQ&s" class="card-img-top" alt="Design 2">
            <div class="card-body">
              <h5 class="card-title">Design 2</h5>
              <p class="card-text">Another stunning piece of work.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <img src="https://avatars.mds.yandex.net/i?id=b507a2b8d9382967a186c654f1eeaa74-5262078-images-taas-consumers&n=27&h=480&w=480" class="card-img-top" alt="Design 3">
            <div class="card-body">
              <h5 class="card-title">Design 3</h5>
              <p class="card-text">Let your imagination flow.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-dark text-white py-3 text-center">
    <p>&copy; 2024 | Designed by [Manikandan]</p>
  </footer>


  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
  
</body>
</html>

```
## About.html
```
<html>
    <head>
        <title>about</title>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    </head>
    <body>
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <div class="container">
              <a class="navbar-brand" href="#">Dribbble Clone</a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                  <li class="nav-item"><a class="nav-link" href="#">Discover</a></li>
                  <li class="nav-item"><a class="nav-link" href="#">Projects</a></li>
                  <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                  <li class="nav-item"><a class="nav-link btn btn-primary text-white" href="#">Sign Up</a></li>
                </ul>
              </div>
            </div>
          </nav>
          <section class="py-5 bg-light" id="about">
            <div class="container">
              <h2 class="text-center mb-4">About Us</h2>
              <p class="text-center">Dribbble Clone is a platform for designers to showcase their work and get inspired. Whether you're a graphic designer, illustrator, or UI/UX expert, our community is here to help you grow and connect with others.</p>
              <div class="row mt-4">
                <div class="col-md-6">
                  <h5>Our Mission</h5>
                  <p>To provide a space for creatives to share their work, gain feedback, and find inspiration from peers around the world.</p>
                </div>
                <div class="col-md-6">
                  <h5>Why Join Us?</h5>
                  <p>By joining Dribbble Clone, you become part of a vibrant community that celebrates creativity and innovation in design.</p>
                </div>
              </div>
            </div>
          </section>
          <footer class="bg-dark text-white py-3 text-center">
            <p>&copy; 2024 | Designed by [Manikandan]</p>
          </footer>
          <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

        
</html>
  
```
## Project.html
```
<html>
    <head>
        <title>project</title>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">


    </head>
    <body>
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <div class="container">
              <a class="navbar-brand" href="#">Dribbble Clone</a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                  <li class="nav-item"><a class="nav-link" href="#">Discover</a></li>
                  <li class="nav-item"><a class="nav-link" href="#">Projects</a></li>
                  <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                  <li class="nav-item"><a class="nav-link btn btn-primary text-white" href="#">Sign Up</a></li>
                </ul>
              </div>
            </div>
          </nav>
          <section class="py-5" id="projects">
            <div class="container">
              <h2 class="text-center mb-4">Projects</h2>
              <p class="text-center">Explore various design projects contributed by our talented community members.</p>
              <div class="row">
                <div class="col-md-4">
                  <div class="card">
                    <img src="https://via.placeholder.com/300" class="card-img-top" alt="Project 1">
                    <div class="card-body">
                      <h5 class="card-title">Project 1</h5>
                      <p class="card-text">A creative web design project.</p>
                    </div>
                  </div>
                </div>
                <div class="col-md-4">
                  <div class="card">
                    <img src="https://via.placeholder.com/300" class="card-img-top" alt="Project 2">
                    <div class="card-body">
                      <h5 class="card-title">Project 2</h5>
                      <p class="card-text">An innovative mobile app design.</p>
                    </div>
                  </div>
                </div>
                <div class="col-md-4">
                  <div class="card">
                    <img src="https://via.placeholder.com/300" class="card-img-top" alt="Project 3">
                    <div class="card-body">
                      <h5 class="card-title">Project 3</h5>
                      <p class="card-text">A branding and identity design.</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </section>
          <footer class="bg-dark text-white py-3 text-center">
            <p>&copy; 2024 | Designed by [Manikandan]</p>
          </footer>
          <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
          

    </body>
</html>
```
## Signup.html
```
<html>
    <head>
        <title>signup</title>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">

    </head>
    <body>
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <div class="container">
              <a class="navbar-brand" href="#">Dribbble Clone</a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                  <li class="nav-item"><a class="nav-link" href="#">Discover</a></li>
                  <li class="nav-item"><a class="nav-link" href="#">Projects</a></li>
                  <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                  <li class="nav-item"><a class="nav-link btn btn-primary text-white" href="#">Sign Up</a></li>
                </ul>
              </div>
            </div>
          </nav>
          <section class="py-5 bg-primary text-white" id="signup">
            <div class="container">
              <h2 class="text-center mb-4">Sign Up</h2>
              <p class="text-center">Join the Dribbble Clone community and start sharing your work today!</p>
              <form class="mx-auto" style="max-width: 500px;">
                <div class="mb-3">
                  <label for="username" class="form-label">Username</label>
                  <input type="text" class="form-control" id="username" placeholder="Enter your username" required>
                </div>
                <div class="mb-3">
                  <label for="email" class="form-label">Email address</label>
                  <input type="email" class="form-control" id="email" placeholder="Enter your email" required>
                </div>
                <div class="mb-3">
                  <label for="password" class="form-label">Password</label>
                  <input type="password" class="form-control" id="password" placeholder="Enter your password" required>
                </div>
                <button type="submit" class="btn btn-light w-100">Sign Up</button>
              </form>
            </div>
          </section>
          <footer class="bg-dark text-white py-3 text-center">
            <p>&copy; 2024 | Designed by [Padmavathi]</p>
          </footer>
          <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    </body>
</html>
```
## OUTPUT:
## Discover.html:
![Screenshot 2024-12-23 185443](https://github.com/user-attachments/assets/d244c654-7a29-42e8-8f9d-e042d6a8f149)


## About.html:
![Screenshot 2024-12-24 213534](https://github.com/user-attachments/assets/2abe70f6-7e90-4b0f-bd77-879387ce5784)



## Project.html:
![Screenshot 2024-12-23 185714](https://github.com/user-attachments/assets/fd510be0-05ad-4ee2-b3fe-606669bdd7f6)


## Signup.html:
![Screenshot 2024-12-23 185744](https://github.com/user-attachments/assets/6cc27e67-5311-4064-94fc-75610de5000c)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
