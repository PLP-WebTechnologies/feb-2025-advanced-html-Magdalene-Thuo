# Advanced HTML5 Elements and Forms

<!DOCTYPE html>
<html lang "en">
<head>
    <meta charset="UTF-8">
    <title>Assignment</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!--List with Roman Numerals-->
    <h1>ON THE MOVE</h1>
    <h1>List of Items</h1>
    <ol type="I">  
        <li> Sports</li>
        <li>Swimming</li>
        <li>Reading</li>
        <li>Dancing</li>
        <li>Yoga</li>
    </ol>

    <!--Image from pexels-->
    <h2>Image from pexels</h2>
    <img src="https://images.pexels.com/photos/20787/pexels-photo.jpg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" alt="Image from pexels" class="image">

    <!--Contact List-->
    <h3>Contact List</h3>
    <table>
        <tr>
            <th>Name</th>
            <th>Phone Number</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>John</td>
            <td>1234567890</td>
            <td>john@gmail.com</td>
        </tr>
        <tr>
            <td>Smith</td>
            <td>0987654321</td>
            <td>smith@gmail.com</td>
        </tr>
        <tr>
            <td>David</td>
            <td>1234567890</td>
            <td>david@gmail.com</td>
        </tr>
    </table>


    <!--Registration Form-->
    <h4>Registration Form</h4>
    <form action="submit.php" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required><br><br>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required><br><br>
        <label for="phone">Phone Number:</label>
        <input type="tel" id="phone" name="phone" required><br><br>
        <input type="submit" value="Submit">

    <!--Drop Down List-->
    <label for="Country">Country:</label>
    <select name="Country" id="Country">
        <option value="">--select--</option>
        <option value="India">India</option>
        <option value="USA">USA</option>
        <option value="UK">UK</option>
        <option value="Australia">Australia</option>
        <option value="Canada">Canada</option>
    </select>
    <br><br>

    <!--Radio Buttons-->
    <label>Gender:</label> 
    <input type="radio" id="Male" name="Gender" value="Male" required>
    <label for="Male">Male</label>
    <input type="radio" id="Female" name="Gender" value="Female" required>
    <label for="Female">Female</label>
    <br><br>

    <!-- Checkboxes -->
    <label>Interests:</label>
    <input type="checkbox" id="sports" name="interests" value="Sports">
    <label for="sports">Sports</label>
    <input type="checkbox" id="music" name="interests" value="Music">
    <label for="music">Music</label>
    <input type="checkbox" id="reading" name="interests" value="Reading">
    <label for="reading">Reading</label>
    <br><br>
    
    <!-- Submit Button -->
    <button type="submit">Register</button>
</form>

</body>
</html>

