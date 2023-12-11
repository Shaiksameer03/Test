<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css">
  <style>
    body {
      padding-top: 56px; /* Adjusted for the fixed navbar height */
    }
    .navbar {
      transition: background-color 0.3s;
    }
    .navbar-scrolled {
      background-color: #333; /* Change background color when scrolled */
    }
  </style>
</head>
<body>

<nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
  <a class="navbar-brand" href="#">Your Company Name</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse justify-content-center" id="navbarNav">
    <ul class="navbar-nav">
      <li class="nav-item active">
        <a class="nav-link" href="#">Home</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">About</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Contact</a>
      </li>
    </ul>
    <ul class="navbar-nav ml-auto">
      <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          Our Menu
        </a>
        <div class="dropdown-menu dropdown-menu-full" aria-labelledby="navbarDropdownMenuLink">
          <a class="dropdown-item" href="#">Chicken</a>
          <a class="dropdown-item" href="#">Beef</a>
          <a class="dropdown-item" href="#">Sushi</a>
        </div>
      </li>
    </ul>
  </div>
</nav>

<!-- Page Content -->
<div class="container">
  <h1 class="mt-5 text-center">Page Heading</h1>
  <!-- Add your content here -->
</div>

<script src="https://code.jquery.com/jquery-3.2.1.slim.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script>

<script>
  // Change navbar background on scroll
  $(window).scroll(function() {
    if ($(this).scrollTop() > 50) {
      $('.navbar').addClass('navbar-scrolled');
    } else {
      $('.navbar').removeClass('navbar-scrolled');
    }
  });
</script>

</body>
</html>






<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
    <title>Your Restaurant Name</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <style>
        body {
            padding-top: 56px; /* Adjust this value according to your fixed navbar height */
        }
        .navbar {
            background-color: #333;
        }
        .navbar-dark .navbar-toggler-icon {
            background-color: #fff;
        }
        .dropdown-menu {
            background-color: #333;
        }
        .dropdown-item {
            color: #fff;
        }
        .jumbotron {
            text-align: center;
            background-color: #f8f9fa;
            margin-bottom: 0;
        }
    </style>
</head>
<body>

<nav class="navbar navbar-expand-lg fixed-top navbar-dark">
    <a class="navbar-brand" href="#">Your Company Name</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown"
            aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavDropdown">
        <ul class="navbar-nav ml-auto">
            <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button"
                   data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                    Menu
                </a>
                <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                    <a class="dropdown-item" href="#" onclick="showItem('chicken')">Chicken</a>
                    <a class="dropdown-item" href="#" onclick="showItem('beef')">Beef</a>
                    <a class="dropdown-item" href="#" onclick="showItem('sushi')">Sushi</a>
                </div>
            </li>
        </ul>
    </div>
</nav>

<div class="jumbotron">
    <h1 class="display-4">Page Heading</h1>
</div>

<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
<script>
    function showItem(item) {
        // Add logic to display information and image for the selected item
        console.log(`Displaying information for ${item}`);
    }
</script>
</body>
</html>

