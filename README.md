<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Store</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css">
    <link rel="stylesheet" href="styles.css"> <!-- custom CSS file -->
</head>
<body>
    <!-- Header Section -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <a class="navbar-brand" href="#">Book Store</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="books.html">Books</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Categories</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">About Us</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Contact</a>
                </li>
            </ul>
            <form class="form-inline my-2 my-lg-0">
                <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
                <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
            </form>
        </div>
    </nav>

    <!-- Carousel Section -->
    <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img class="d-block w-100" src="image1.jpg" alt="First slide">
            </div>
            <div class="carousel-item">
                <img class="d-block w-100" src="image2.jpg" alt="Second slide">
            </div>
            <div class="carousel-item">
                <img class="d-block w-100" src="image3.jpg" alt="Third slide">
            </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
        </a>
    </div>

    <!-- Book Cards Section -->
    <div class="container">
        <div class="row">
            <div class="col-md-3">
                <div class="card">
                    <img class="card-img-top" src="book1.jpg" alt="Book 1">
                    <div class="card-body">
                        <h5 class="card-title">Book 1</h5>
                        <p class="card-text">Author: John Doe</p>
                        <p class="card-text">$19.99</p>
                        <button class="btn btn-primary">Add to Cart</button>
                        <button class="btn btn-secondary">View Details</button>
                    </div>
                </div>
            </div>
            <div class="col-md-3">
                <div class="card">
                    <!-- Book 2 details -->
                </div>
            </div>
            <!-- Add more book cards here -->
        </div>
    </div>

    <!-- Footer Section -->
    <footer class="footer">
        <div class="container">
            <div class="row">
                <div class="col-md-4">
                    <h5>Follow Us</h5>
                    <ul class="list-unstyled">
                        <li><a href="#">Facebook</a></li>
                        <li><a href="#">Twitter</a></li>
                        <li><a href="#">Instagram</a></li>
                    </ul>
                </div>
                <div class="
