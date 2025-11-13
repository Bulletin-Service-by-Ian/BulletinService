<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Bulletin Service</title>
  <link href="https://fonts.googleapis.com/css2?family=Comic+Neue:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Comic Neue', cursive;
      margin: 0;
      padding: 0;
      background: #fffbea;
      color: #333;
    }
    header {
      background-color: #ffcc5c;
      padding: 20px;
      text-align: center;
      position: sticky;
      top: 0;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }
    header img {
      max-height: 80px;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
      color: #ff6f61;
    }
    nav a:hover {
      color: #6b5b95;
    }
    section {
      padding: 40px 20px;
      text-align: center;
    }
    h1, h2 {
      color: #ff6f61;
    }
    .button {
      display: inline-block;
      background-color: #6b5b95;
      color: white;
      padding: 15px 25px;
      margin: 10px;
      border-radius: 12px;
      cursor: pointer;
      text-decoration: none;
      font-weight: bold;
      transition: transform 0.2s, background-color 0.2s;
      border: none;
    }
    .button:hover {
      transform: scale(1.1);
      background-color: #ff6f61;
    }
    input, select {
      padding: 10px;
      margin: 10px 0;
      border-radius: 8px;
      border: 1px solid #ccc;
      font-size: 16px;
    }
    footer {
      background-color: #ffcc5c;
      padding: 20px;
      text-align: center;
    }
  </style>
</head>
<body>

<header>
  <img src="YOUR_IMAGE_HERE.png" alt="Bulletin Logo">
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#orders">Orders</a>
  </nav>
</header>

<section id="home">
  <h1>Welcome to Our Bulletin Service!</h1>
  <p>Fun, fast, and easy bulletin posting at your fingertips.</p>
  <a class="button" href="#orders">Place an Order</a>
</section>

<section id="about">
  <h2>About Us</h2>
  <p>We started this bulletin service to make sharing news and announcements playful and colorful. Easy to use, and guaranteed to brighten your day!</p>
</section>

<section id="orders">
  <h2>Place Your Order</h2>
  <p>Select your order and submit your email to send it directly to us:</p>
  <form action="https://formspree.io/f/mqawavka" method="POST">
    <label for="order">Select Your Order:</label><br>
    <select id="order" name="order" required>
      <option value="">--Choose--</option>
      <option value="Put items up">Put items up</option>
      <option value="Take items down">Take items down</option>
      <option value="Replace items">Replace items</option>
      <option value="Replace letters">Replace letters</option>
    </select><br>
    <input type="email" name="_replyto" placeholder="Your email" required><br>
    <button type="submit" class="button">Send Order</button>
  </form>
</section>

<footer>
  <p>&copy; 2025 My Bulletin Service</p>
</footer>

</body>
</html>
