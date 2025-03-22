# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨
THE CODE

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML5 Elements Demo</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid black;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>
    <h1>HTML5 Elements Implementation</h1>
    
    <!-- Ordered List with Roman Numerals -->
    <h2>Ordered List</h2>
    <ol type="I">
        <li>First Item</li>
        <li>Second Item</li>
        <li>Third Item</li>
    </ol>
    
    <!-- External Image from Pexels -->
    <h2>External Image</h2>
    <img src="https://www.pexels.com/photo/beautiful-scenery-12345/" alt="Beautiful Scenery" width="500">
    
    <!-- Contacts Table -->
    <h2>Contacts Table</h2>
    <table>
        <tr>
            <th>Name</th>
            <th>Address</th>
            <th>Mobile</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>John Doe</td>
            <td>123 Street, City</td>
            <td>+1234567890</td>
            <td>john@example.com</td>
        </tr>
        <tr>
            <td>Jane Smith</td>
            <td>456 Avenue, City</td>
            <td>+0987654321</td>
            <td>jane@example.com</td>
        </tr>
        <tr>
            <td>Mark Johnson</td>
            <td>789 Road, City</td>
            <td>+1122334455</td>
            <td>mark@example.com</td>
        </tr>
        <tr>
            <td>Lisa White</td>
            <td>321 Boulevard, City</td>
            <td>+5566778899</td>
            <td>lisa@example.com</td>
        </tr>
        <tr>
            <td>Paul Brown</td>
            <td>654 Lane, City</td>
            <td>+6677889900</td>
            <td>paul@example.com</td>
        </tr>
    </table>
    
    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form action="#" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your name" required>
        <br><br>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required>
        <br><br>
        
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter your password" required>
        <br><br>
        
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required>
        <br><br>
        
        <label for="gender">Gender:</label>
        <input type="radio" id="male" name="gender" value="male" required> Male
        <input type="radio" id="female" name="gender" value="female" required> Female
        <br><br>
        
        <label for="country">Country:</label>
        <select id="country" name="country" required>
            <option value="">Select Country</option>
            <option value="USA">USA</option>
            <option value="Canada">Canada</option>
            <option value="UK">UK</option>
        </select>
        <br><br>
        
        <label>Interests:</label>
        <input type="checkbox" id="sports" name="interests" value="sports"> Sports
        <input type="checkbox" id="music" name="interests" value="music"> Music
        <input type="checkbox" id="reading" name="interests" value="reading"> Reading
        <br><br>
        
        <input type="submit" value="Register">
    </form>
    
    <!-- Audio Element -->
    <h2>Audio</h2>
    <audio controls>
        <source src="audio.mp3" type="audio/mp3">
        Your browser does not support the audio element.
    </audio>
    
    <!-- Video Element -->
    <h2>Video</h2>
    <video width="500" controls>
        <source src="video.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</body>
</html>
