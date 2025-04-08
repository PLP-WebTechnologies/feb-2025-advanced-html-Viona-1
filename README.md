<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML5 Multimedia Webpage</title>
</head>
<body>

    <h1>Welcome to My HTML5 Webpage</h1>

    <!-- Ordered List with Roman Numerals -->
    <h2>Steps to Learn Web Development</h2>
    <ol type="I">
        <li>Learn HTML</li>
        <li>Learn CSS</li>
        <li>Learn JavaScript</li>
        <li>Practice Projects</li>
    </ol>

    <!-- External Image from Pexels -->
    <h2>Beautiful Nature</h2>
    <img src="https://images.pexels.com/photos/34950/pexels-photo.jpg" alt="Nature Image" width="500">

    <!-- Table of 5 Contacts -->
    <h2>Contact List</h2>
    <table border="1">
        <tr>
            <th>Name</th>
            <th>Address</th>
            <th>Mobile</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>Viona Enid</td>
            <td>Nairobi</td>
            <td>0712345678</td>
            <td>enid@gmail.com</td>
        </tr>
        <tr>
            <td>Mary Jane</td>
            <td>Mombasa</td>
            <td>0723456789</td>
            <td>mary@gmail.com</td>
        </tr>
        <tr>
            <td>Peter Kimani</td>
            <td>Kisumu</td>
            <td>0734567890</td>
            <td>peter@gmail.com</td>
        </tr>
        <tr>
            <td>Sarah Auma</td>
            <td>Nakuru</td>
            <td>0745678901</td>
            <td>sarah@gmail.com</td>
        </tr>
        <tr>
            <td>James Bond</td>
            <td>Eldoret</td>
            <td>0756789012</td>
            <td>bond@gmail.com</td>
        </tr>
    </table>

    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form action="#" method="post">
        <!-- Name -->
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your name" required><br><br>

        <!-- Email -->
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

        <!-- Password -->
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter password" required minlength="6"><br><br>

        <!-- Date -->
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required><br><br>

        <!-- Dropdown -->
        <label for="country">Select Country:</label>
        <select id="country" name="country" required>
            <option value="">--Select--</option>
            <option value="Kenya">Kenya</option>
            <option value="Uganda">Uganda</option>
            <option value="Tanzania">Tanzania</option>
        </select><br><br>

        <!-- Radio Buttons -->
        <label>Gender:</label><br>
        <input type="radio" name="gender" value="Male" required> Male
        <input type="radio" name="gender" value="Female" required> Female<br><br>

        <!-- Checkboxes -->
        <label>Hobbies:</label><br>
        <input type="checkbox" name="hobbies" value="Reading"> Reading
        <input type="checkbox" name="hobbies" value="Music"> Music
        <input type="checkbox" name="hobbies" value="Sports"> Sports<br><br>

        <!-- Submit Button -->
        <input type="submit" value="Register">
    </form>

    <!-- Multimedia Elements -->
    <h2>Audio Clip</h2>
    <audio controls>
        <source src="audio.mp3" type="audio/mpeg">
        Your browser does not support audio.
    </audio>

    <h2>Video Clip</h2>
    <video width="500" controls>
        <source src="video.mp4" type="video/mp4">
        Your browser does not support video.
    </video>

</body>
</html>
