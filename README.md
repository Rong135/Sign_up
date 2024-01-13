<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Sign Up Form</title>
  <link rel="stylesheet" href="CSS new.css">
</head>
<body>

    <div class="container">
        <form id="signupForm" onsubmit="submitForm()">
            <h2>Sign Up</h2>
            <label for="username">Username:</label>
            <input type="text" id="username" required>

            <label for="email">Email:</label>
            <input type="email" id="email" required>

            <label for="password">Password:</label>
            <input type="password" id="password" required>

            <button type="submit">Sign Up</button>
        </form>
    </div>

    <script src="js new.js"></script>
</body>
</html>
