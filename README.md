<!DOCTYPE html>
<html>
  <html>

  <title>Timer Example</title>
  <script>
    function startTimer() {
      var seconds = 10;
      var countdown = setInterval(function() {
        document.getElementById("timer").innerHTML = seconds + " seconds remaining";
        seconds--;
        if (seconds < 0) {
          clearInterval(countdown);
          document.getElementById("timer").innerHTML = "Timer has ended!";
        }
      }, 1000);
    }
  </script>
</head>
<body>
  <h1>Timer Example</h1>
  <button onclick="startTimer()">Start Timer</button>
  <p id="timer"></p>
</body>
</html>
  <head>
    <title>My Marketplace</title>
    <link rel="stylesheet" href="webb.css">
  </head>
  <body>
    <header>
      <h1>digital Marketing</h1>
      <nav>
        <ul>
          <li><a href="#">Products</a></li>
          <li><a href="#">Services</a></li>
          <li><a href="movie1.html">Shopping Cart</a></li>
          <li><a href="login.html">Log In</a></li>
         

        </ul>
      </nav>
    </header>
    <main>
      <h2>Welcome to My Marketplace</h2>
      <p>Find the best products and services from trusted sellers.</p>
      <a href="#" class="cta-button">Shop Now</a>
    </main>
    <div class="container">
		<img src="./mark" alt="Hospital Logo">
        <img src="./mark" alt="Hospital Logo">
        <style>
          /* Footer styling */
          footer {
            background-color: #504d4d;
            color: #fff;
            padding: 20px;
            text-align: center;
          }
      
          /* Link styling */
          footer a {
            color: #fff;
            text-decoration: none;
            padding: 0 10px;
          }
      
          footer a:hover {
            text-decoration: underline;
          }
        </style>
      </head>
      <body>
        <!-- Main content here -->
        <h1>Marketplace</h1>
        <p>Check out our latest product</p>
      
        <footer>
          <!-- Footer content here -->
          <p>&copy; 2023 digital market</p>
          <nav>
            <a href="#">Home</a>
            <a href="./movie.html">Movies</a>
            <a href="#">About Us</a>
            <a href="./login.html">Contact Us</a>
          </nav>
        </footer>
        
        
        
    <footer>
      <p>&copy; 2023 My Marketplace</p>
    </footer>
  </body>
</html>
