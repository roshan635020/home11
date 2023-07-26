<!DOCTYPE html>
<html>
<head>
  <title>Canadian Plumbing Services</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Canadian Plumbing Services</h1>
    <!-- Add navigation menu here -->
  </header>

  <main>
    <section id="services">
      <h2>Our Services</h2>
      <ul>
        <li>Drain Cleaning</li>
        <li>Leak Repair</li>
        <li>Water Heater Installation</li>
        <li>Pipe Replacement</li>
        <!-- Add more services as needed -->
      </ul>
    </section>

    <section id="contact">
      <h2>Contact Us</h2>
      <p>For any inquiries or to request our services, please fill out the form below:</p>
      <form action="contact.php" method="POST">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="message">Message:</label>
        <textarea id="message" name="message" required></textarea>

        <button type="submit">Submit</button>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2023 Canadian Plumbing Services. All rights reserved.</p>
  </footer>
</body>
</html>
