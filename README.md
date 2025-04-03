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

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Multimedia-rich HTML5 webpage with forms, images, and tables">
    <title>Advanced HTML5 Elements and Forms</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header, nav, main, footer {
            padding: 20px;
        }
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
        }
        nav {
            background-color: #f4f4f4;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #333;
        }
        footer {
            background-color: #222;
            color: white;
            text-align: center;
            padding: 10px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: #4CAF50;
            color: white;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Welcome to My Page</h1>
    </header>

    <!-- Navigation Menu -->
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- Main Content Section -->
    <main>
        <section>
            <h2>About Page</h2>
            <p>Thank you for visiting my page!</p>
        </section>

        <!-- Ordered List with Roman Numerals -->
        <section>
            <h2>Ordered List</h2>
            <ol type="I">
                <li>Item One</li>
                <li>Item Two</li>
                <li>Item Three</li>
            </ol>
        </section>

        <!-- External Image -->
        <section>
            <h2>Image from Pexels</h2>
            <img src="https://images.pexels.com/photos/1108099/pexels-photo-1108099.jpeg" alt="Beautiful Scenery" width="600">
        </section>

        <!-- Contacts Table -->
        <section>
            <h2>Contact List</h2>
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
                    <td>Michael Brown</td>
                    <td>789 Road, City</td>
                    <td>+1122334455</td>
                    <td>michael@example.com</td>
                </tr>
                <tr>
                    <td>Sarah Wilson</td>
                    <td>321 Lane, City</td>
                    <td>+6677889900</td>
                    <td>sarah@example.com</td>
                </tr>
                <tr>
                    <td>David Johnson</td>
                    <td>654 Street, City</td>
                    <td>+5544332211</td>
                    <td>david@example.com</td>
                </tr>
            </table>
        </section>

        <!-- Registration Form -->
        <section>
            <h2>Registration Form</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" placeholder="Enter your name" required><br><br>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>
                
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" placeholder="Enter your password" required><br><br>
                
                <label for="dob">Date of Birth:</label>
                <input type="date" id="dob" name="dob" required><br><br>
                
                <label>Gender:</label>
                <input type="radio" id="male" name="gender" value="Male"> <label for="male">Male</label>
                <input type="radio" id="female" name="gender" value="Female"> <label for="female">Female</label>
                <input type="radio" id="other" name="gender" value="Other"> <label for="other">Other</label><br><br>
                
                <label for="country">Country:</label>
                <select id="country" name="country">
                    <option value="">Select Country</option>
                    <option value="USA">USA</option>
                    <option value="UK">UK</option>
                    <option value="Canada">Canada</option>
                </select><br><br>
                
                <label>Interests:</label>
                <input type="checkbox" id="sports" name="interests" value="Sports"> <label for="sports">Sports</label>
                <input type="checkbox" id="music" name="interests" value="Music"> <label for="music">Music</label>
                <input type="checkbox" id="reading" name="interests" value="Reading"> <label for="reading">Reading</label><br><br>
                
                <input type="submit" value="Register">
            </form>
        </section>
    </main>

    <!-- Footer Section -->
    <footer>
        <p>Contact us at: mikethrills@gmail.com</p>
        <p>&copy; 2025 My Website</p>
    </footer>
</body>
</html>
