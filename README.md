<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Feedback Form</title>
 <style>
   body {
  margin: 0;
  font-family: 'Poppins', sans-serif;
  background: #f4f4f9;
  color: #333;
}

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px 40px;
  background: #1e1e2e;
  color: #fff;
}
.btn:hover {
  background: #3867d6;
}

.fade-in {
  opacity: 0;
  animation: fadeIn 1s forwards;
}

.delay {
  animation-delay: 0.5s;
}

@keyframes fadeIn {
  to { opacity: 1; }
}

.about-section {
  margin: 80px auto;
  width: 70%;
  text-align: center;
}

.footer {
  background: #1e1e2e;
  color: white;
  padding: 20px;
  text-align: center;
  margin-top: 80px;
}
/* --------- General Page Styling --------- */
body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
  background: #f5f5f5;
  color: #333;
}

/* --------- Navbar --------- */
.navbar {
  background: #1a73e8;
  color: #fff;
  padding: 15px 30px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.navbar .logo {
  font-size: 1.5rem;
  font-weight: bold;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 20px;
}

.nav-links li a {
  text-decoration: none;
  color: #fff;
  font-weight: 500;
  transition: 0.3s ease;
}

.nav-links li a:hover,
.nav-links li a.active {
  color: #ffd54f;
}

/* --------- Form Container --------- */
.form-container {
  width: 90%;
  max-width: 600px;
  background: #fff;
  margin: 40px auto;
  padding: 30px;
  border-radius: 10px;
  box-shadow: 0 0 12px rgba(0, 0, 0, 0.1);
}

.form-container h1 {
  margin-bottom: 10px;
}

.form-container p {
  margin-bottom: 25px;
  color: #555;
}

/* --------- Form Styling --------- */
.feedback-form label {
  font-weight: 600;
  display: block;
  margin-bottom: 5px;
}

.feedback-form input,
.feedback-form textarea {
  width: 100%;
  padding: 12px;
  margin-bottom: 20px;
  border-radius: 6px;
  border: 1px solid #ccc;
  font-size: 1rem;
}

.feedback-form input:focus,
.feedback-form textarea:focus {
  border-color: #1a73e8;
  outline: none;
}


.btn {
  background: #1a73e8;
  color: white;
  padding: 12px 20px;
  font-size: 1rem;
  border: none;
  border-radius: 6px;
  cursor: pointer;
  transition: 0.3s;
}

.btn:hover {
  background: #155dc2;
}
.navbar .nav-links {
  list-style: none;
  display: flex;
  gap: 20px;
}

.navbar .nav-links li a {
  color: white;
  text-decoration: none;
  font-weight: 500;
}

.navbar .nav-links .active {
  border-bottom: 2px solid #fff;
}

.home-container {
  text-align: center;
  margin-top: 120px;
}

.btn {
  display: inline-block;
  padding: 12px 24px;
  background: #4b7bec;
  color: white;
  text-decoration: none;
  border-radius: 6px;
  font-weight: 600;
  transition: 0.3s ease;
}



.footer {
  text-align: center;
  padding: 20px;
  background: #1a73e8;
  color: white;
  margin-top: 40px;
}
 </style>
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
