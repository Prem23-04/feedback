<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Feedback Form</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <nav class="navbar">
    <div class="logo">My Website</div>
    <ul class="nav-links">
      <li><a href="home.html">Home</a></li>
      <li><a href="index.html" class="active">Feedback</a></li>
    </ul>
  </nav>

  <div class="form-container">
    <h1>Feedback Form</h1>
    <p>We love to hear from you! Please fill out the form below.</p>

    <form action="#" method="post" class="feedback-form">

      <label for="name">Name:</label>
      <input type="text" id="name" name="name" placeholder="Your name" required><br>

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" placeholder="Your email" required><br>

      <!-- ⭐ Rating Dropdown -->
      <label for="rating">Rating:</label>
      <select id="rating" name="rating" required>
        <option value="" disabled selected>Select rating</option>
        <option value="1">1 ⭐</option>
        <option value="2">2 ⭐</option>
        <option value="3">3 ⭐</option>
        <option value="4">4 ⭐</option>
        <option value="5">5 ⭐</option>
      </select>
      <br><br>

      <label for="feedback">Feedback:</label>
      <textarea id="feedback" name="feedback" placeholder="Your feedback" rows="5" required></textarea><br>

      <button type="submit" class="btn" href="thankyou.html">Submit Feedback</button>
    </form>
  </div>

  <footer class="footer">
    <p>© 2025 Your Name | All Rights Reserved</p>
  </footer>

</body>
</html># feedback
