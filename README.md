<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Register</title>
    <style>
        body {
         font-family: Arial; background: #f4f4f4; padding: 20px; 
             }
        form {
 max-width: 300px; margin: auto; background: white; padding: 15px; border-radius: 5px; box-shadow: 0 0 5px rgba(0,0,0,0.1); }
        input { 
width: 100%; padding: 8px; margin: 5px 0; }
        input[type="submit"] { 
background: #4CAF50; color: white; border: none; cursor: pointer; }
        input[type="submit"]:hover { background: #45a049; }
    </style>
</head>
<body>

<form action="/submit-registration" method="POST">
    <h2>Register</h2>
    <input type="text" name="name" placeholder="Full Name" required>
    <input type="email" name="email" placeholder="Email" required>
    <input type="password" name="password" placeholder="Password" required>
    <input type="submit" value="Register">
</form>

</body>
</html>
