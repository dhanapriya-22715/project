# Project Responsive Web Design using Bootstrap
# Date:  14-12-2024
# Developed by : DHANAPPRIYA S

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
Home Page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <a class="navbar-brand" href="#">UrbGlam</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="about us.html">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="boostrp.html">Work</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="contact.html">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class=" text-white text-center py-5" style="background-image: url(bc.jpg); width:100%;height: 200px; background-repeat: no-repeat;background-size: cover;" >
        <div class="container">
            <h1 style="font-family: 'Times New Roman'; font-size: xxx-large;color:rgb(2, 22, 53);">Welcome to UrbGlam</h1>
            <p class="lead" style="font-size: x-large;color: rgb(2, 22, 53);">Urban. Glamorous. Unstoppable</p>
        </div>
    </header>
    <header class=" text-white text-center py-5" style="background-image: url(New\ Looks\ In\ Autumn\ Style.png); width:100%;height: 500px;" ></header>

    <!-- Work Section -->
    <section id="work" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center">MOST LOVED</h2>
            <div class="row">
                <div class="col-md-3">
                    <div class="card">
                        <img src="C:\Users\admin\Desktop\Django\Figma\Screenshot (98).png" class="card-img-top" alt="Work Example">
                        <div class="card-body">
                            <h5 class="card-title">Necklace</h5>
                            <p class="card-text">Radiant Butterfly Tassel Necklace          </p>
                            <p>Rs.1200</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card">
                        <img src="C:\Users\admin\Desktop\Django\Figma\Screenshot 2024-12-25 211056.png" class="card-img-top" alt="Work Example">
                        <div class="card-body">
                            <h5 class="card-title">Ring</h5>
                            <p class="card-text">Gossamer Mary Ring</p>
                            <p>Rs.1199</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card">
                        <img src="C:\Users\admin\Desktop\Django\Figma\Screenshot 2024-12-25 211515.png" class="card-img-top" alt="Work Example">
                        <div class="card-body">
                            <h5 class="card-title">Earrings</h5>
                            <p class="card-text">Sapphire Ribbon Gold Earrings</p>
                            <p>Rs.749</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card">
                        <img src="C:\Users\admin\Desktop\Django\Figma\Screenshot (95).png" class="card-img-top" alt="Work Example">
                        <div class="card-body">
                            <h5 class="card-title">Anklets</h5>
                            <p class="card-text">A brief description of the project.</p>
                            <p>Rs.999</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-3">
        <div class="container">
            <p>&copy; 2024 Dhanappriya. All rights reserved.</p>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
Products
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <a class="navbar-brand" href="#">UrbGlam</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="about us.html">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="boostrp.html">Work</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="contact.html">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class=" text-white text-center py-5" style="background-image: url(bc.jpg); width:100%;height: 200px; background-repeat: no-repeat;background-size: cover;" >
        <div class="container">
            <h1 style="font-family: 'Times New Roman'; font-size: xxx-large;color:rgb(2, 22, 53);">Welcome to UrbGlam</h1>
            <p class="lead" style="font-size: x-large;color: rgb(2, 22, 53);">Urban. Glamorous. Unstoppable</p>
        </div>
    </header>
    <header class=" text-white text-center py-5" style="background-image: url(New\ Looks\ In\ Autumn\ Style.png); width:100%;height: 500px;" ></header>

    <!-- Work Section -->
    <section id="work" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center">MOST LOVED</h2>
            <div class="row">
                <div class="col-md-3">
                    <div class="card">
                        <img src="C:\Users\admin\Desktop\Django\Figma\Screenshot (98).png" class="card-img-top" alt="Work Example">
                        <div class="card-body">
                            <h5 class="card-title">Necklace</h5>
                            <p class="card-text">Radiant Butterfly Tassel Necklace          </p>
                            <p>Rs.1200</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card">
                        <img src="C:\Users\admin\Desktop\Django\Figma\Screenshot 2024-12-25 211056.png" class="card-img-top" alt="Work Example">
                        <div class="card-body">
                            <h5 class="card-title">Ring</h5>
                            <p class="card-text">Gossamer Mary Ring</p>
                            <p>Rs.1199</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card">
                        <img src="C:\Users\admin\Desktop\Django\Figma\Screenshot 2024-12-25 211515.png" class="card-img-top" alt="Work Example">
                        <div class="card-body">
                            <h5 class="card-title">Earrings</h5>
                            <p class="card-text">Sapphire Ribbon Gold Earrings</p>
                            <p>Rs.749</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card">
                        <img src="C:\Users\admin\Desktop\Django\Figma\Screenshot (95).png" class="card-img-top" alt="Work Example">
                        <div class="card-body">
                            <h5 class="card-title">Anklets</h5>
                            <p class="card-text">A brief description of the project.</p>
                            <p>Rs.999</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-3">
        <div class="container">
            <p>&copy; 2024 Dhanappriya. All rights reserved.</p>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
Contact
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <a class="navbar-brand" href="#">UrbGlam</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="bootstrap-2.html">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="about us.html">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link active" href="contact.html">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Contact Section -->
    <section class="py-5">
        <div class="container">
            <h2 class="text-center">Contact Us</h2>
            <p class="text-center">We would love to hear from you! Feel free to reach out for collaborations, inquiries, or just to say hi.</p>

            <div class="row">
                <!-- Contact Form -->
                <div class="col-md-6">
                    <h4>Send Us a Message</h4>
                    <form>
                        <div class="mb-3">
                            <label for="name" class="form-label">Name</label>
                            <input type="text" class="form-control" id="name" placeholder="Your Name">
                        </div>
                        <div class="mb-3">
                            <label for="email" class="form-label">Email</label>
                            <input type="email" class="form-control" id="email" placeholder="Your Email">
                        </div>
                        <div class="mb-3">
                            <label for="message" class="form-label">Message</label>
                            <textarea class="form-control" id="message" rows="3" placeholder="Your Message"></textarea>
                        </div>
                        <button type="submit" class="btn btn-primary">Submit</button>
                    </form>
                </div>

                <!-- Contact Details -->
                <div class="col-md-6">
                    <h4>Contact Details</h4>
                    <ul class="list-unstyled">
                        <li><strong>Email:</strong> contact@dribbbleclone.com</li>
                        <li><strong>Phone:</strong> +1 (123) 456-7890</li>
                        <li><strong>Address:</strong> 123 Creative Lane, Design City, DC 45678</li>
                    </ul>

                    <h4>Follow Us</h4>
                    <ul class="list-inline">
                        <li class="list-inline-item">
                            <a href="#" class="text-decoration-none">Facebook</a>
                        </li>
                        <li class="list-inline-item">
                            <a href="#" class="text-decoration-none">Twitter</a>
                        </li>
                        <li class="list-inline-item">
                            <a href="#" class="text-decoration-none">Instagram</a>
                        </li>
                        <li class="list-inline-item">
                            <a href="#" class="text-decoration-none">LinkedIn</a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-3">
        <div class="container">
            <p>&copy; 2024 Dhanappriya. All rights reserved.</p>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
about
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <a class="navbar-brand" href="#">UrbGlam</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="bootstrap-2.html">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="about us.html">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link active" href="contact.html">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Contact Section -->
    <section class="py-5">
        <div class="container">
            <h2 class="text-center">Contact Us</h2>
            <p class="text-center">We would love to hear from you! Feel free to reach out for collaborations, inquiries, or just to say hi.</p>

            <div class="row">
                <!-- Contact Form -->
                <div class="col-md-6">
                    <h4>Send Us a Message</h4>
                    <form>
                        <div class="mb-3">
                            <label for="name" class="form-label">Name</label>
                            <input type="text" class="form-control" id="name" placeholder="Your Name">
                        </div>
                        <div class="mb-3">
                            <label for="email" class="form-label">Email</label>
                            <input type="email" class="form-control" id="email" placeholder="Your Email">
                        </div>
                        <div class="mb-3">
                            <label for="message" class="form-label">Message</label>
                            <textarea class="form-control" id="message" rows="3" placeholder="Your Message"></textarea>
                        </div>
                        <button type="submit" class="btn btn-primary">Submit</button>
                    </form>
                </div>

                <!-- Contact Details -->
                <div class="col-md-6">
                    <h4>Contact Details</h4>
                    <ul class="list-unstyled">
                        <li><strong>Email:</strong> contact@dribbbleclone.com</li>
                        <li><strong>Phone:</strong> +1 (123) 456-7890</li>
                        <li><strong>Address:</strong> 123 Creative Lane, Design City, DC 45678</li>
                    </ul>

                    <h4>Follow Us</h4>
                    <ul class="list-inline">
                        <li class="list-inline-item">
                            <a href="#" class="text-decoration-none">Facebook</a>
                        </li>
                        <li class="list-inline-item">
                            <a href="#" class="text-decoration-none">Twitter</a>
                        </li>
                        <li class="list-inline-item">
                            <a href="#" class="text-decoration-none">Instagram</a>
                        </li>
                        <li class="list-inline-item">
                            <a href="#" class="text-decoration-none">LinkedIn</a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-3">
        <div class="container">
            <p>&copy; 2024 Dhanappriya. All rights reserved.</p>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```
# OUTPUT:
![Screenshot (99)](https://github.com/user-attachments/assets/0f146ac3-24a6-44bc-93a7-a4897b9f98ba)
![Screenshot (100)](https://github.com/user-attachments/assets/65590ffa-aa67-4ee7-8f16-7e34a24a692d)
![Screenshot (101)](https://github.com/user-attachments/assets/e2bf7401-feac-494d-990b-baaf98d39622)
![Screenshot (102)](https://github.com/user-attachments/assets/c65be443-e4c2-49d7-a3b7-a6ecb4d4bcaa)
![Screenshot (103)](https://github.com/user-attachments/assets/75fcb136-e35e-45c0-b7c1-30ac6542ad04)
![Screenshot (104)](https://github.com/user-attachments/assets/f8ac6b63-3d1c-4338-b486-7ee58c1414a7)
![Screenshot (105)](https://github.com/user-attachments/assets/aeb58243-dbff-4bb3-936b-0bb8c9cb323b)

# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
