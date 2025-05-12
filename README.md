<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>FAMCO Carpentry</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <!-- Hero Section -->
  <section id="hero">
    <div class="overlay">
      <img src="f.png" alt="FAMCO Carpentry Logo" class="logo" />
      <h1>Welcome to FAMCO Carpentry</h1>
      <button onclick="document.getElementById('form-section').scrollIntoView({ behavior: 'smooth' });">
        Pre-Order Now
      </button>
    </div>
  </section>

  <!-- Form Section -->
  <section id="form-section">
    <h2>Pre-order Form</h2>
    <form action="send.php" method="POST">
      <label>Full Name:
        <input type="text" name="name" required />
      </label>
      <label>Email Address:
        <input type="email" name="email" required />
      </label>
      <label>Phone Number:
        <input type="tel" name="phone" required />
      </label>
      <label>Language:
        <select name="language" required>
          <option value="English">English</option>
          <option value="Spanish">Spanish</option>
        </select>
      </label>
      <button type="submit">Submit</button>
    </form>
  </section>
</body>
</html>
