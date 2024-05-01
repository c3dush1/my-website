<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Profile</title>
  <link rel="stylesheet" href="style.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css"> <!-- Font Awesome CSS -->
</head>
<body>
  <header>
    <div class="profile">
      <img src="pic.jpg" alt="Artist Profile Picture">
      <h1>cedushi</h1>
    </div>
    <div class="social-media">
      <a href="#" onclick="showMessage()"><i class="fab fa-instagram"></i></a> <!-- Instagram icon -->
      <a href="https://youtube.com/@cedushi20?si=hV8kcW9Isyk0peZP"><i class="fab fa-youtube"></i></a> <!-- YouTube icon -->
    </div>
  </header>
  
  <main>
    <section class="popular-tracks">
      <h2>Unreleased Songs</h2>
      <ul>
        <li>forever i've fallen</li>
        <li>rollercoaster</li>
        <li>alone</li>
        <!-- Add more popular tracks here -->
      </ul>
    </section>
    
    <section class="about">
      <h2>About</h2>
      <p>is a aspiring musician, singer, song writter beginning his career in music with a genre of indie acoustic.He also has a band named The Hersheys that also soon to rise, cedushi will share all his feelings by realising his composed songs and will be out soon.</p>
    </section>

    <section class="photo-gallery">
      <h2>Photo Gallery</h2>
      <div class="gallery-images">
        <img src="pic1.jpg" alt="Gallery Image 1">
        <img src="pic2.jpg" alt="Gallery Image 2">
        <img src="pic3.jpg" alt="Gallery Image 3">
        <!-- Add more gallery images here -->
      </div>
    </section>
  </main>

  <footer>
    <p>&copy; 2024 Music Artist. All rights reserved.</p>
  </footer>

  <!-- JavaScript for showing message -->
  <script>
    function showMessage() {
      alert("Not yet implemented");
    }
  </script>
</body>
</html>
