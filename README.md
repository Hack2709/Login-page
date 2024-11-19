<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Login Page</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="login-container">
    <div class="login-form">
      <h1>Login</h1>
      <form action="#">
        <label for="username">Username</label>
        <input type="text" id="username" placeholder="Type your username" required>
        
        <label for="password">Password</label>
        <input type="password" id="password" placeholder="Type your password" required>
        
        <a href="#" class="forgot-password">Forgot password?</a>
        
        <button type="submit" class="login-btn">LOGIN</button>
      </form>
      <p>Or Sign Up Using</p>
      <div class="social-login">
        <a href="#" class="social-btn facebook">f</a>
        <a href="#" class="social-btn twitter">t</a>
        <a href="#" class="social-btn google">g</a>
      </div>
      <p><a href="#" class="signup-link">SIGN UP</a></p>
    </div>
  </div>
</body>
</html>
