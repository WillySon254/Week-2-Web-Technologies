# Week-2-Web-Technologies
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My web Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Registration Form</h1>
    <!-- Basic Registration Form -->
<form action="/submit" method="POST">
    <label for="name">Name:</label><br>
    <input type="text" id="name" name="name" required><br><br>

    <label for="email">Email:</label><br>
    <input type="email" id="email" name="email" required><br><br>

    <label for="phone">Phone Number:</label><br>
    <input type="tel" id="phone" name="phone" required><br><br>

    <button type="submit">Register</button>
</form>

<!-- Table displaying common user information -->
<h2>Common User Information</h2>
<table border="1px">
    <thead>
        <tr>
            <th>Name</th>
            <th>Email</th>
            <th>Phone Number</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>John Doe</td>
            <td>john.doe@example.com</td>
            <td>+1234567890</td>
        </tr>
        <tr>
            <td>Jane Smith</td>
            <td>jane.smith@example.com</td>
            <td>+0987654321</td>
        </tr>
    </tbody>
</table>

<!-- An image -->
<h2>Sample Image</h2>
<img src="Flower 2.jpg" alt="Sample Image of Flower" width="500px" height="300px">

<!-- External link to Google -->
<p>Visit <a href="https://google.com" target="_blank">Google</a> for more information.</p>
    
</body>
</html>







body{
    background-color: rgb(28, 218, 113);
    margin: 0;
    padding: 20px;
    /*align-items: center;*/
}
/*form{
    width: 300px;
    margin: 0 auto;
    padding: 20px;
    border: 1px solid #ccc;
    border-radius: 5px;*/
    /*align-items: normal;*/
label{
    display: block;
    margin-bottom: 5px;
}
h1{
    align-items: center;
    color: rgb(226, 250, 8);
}
label{
    size: 40px;
}
table{
    border-style: none;
}
