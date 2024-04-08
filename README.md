<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>More Advanced Website</title>
    <style>
        /* Advanced CSS styles */
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: #444;
            color: #fff;
            padding: 10px;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        nav ul li {
            display: inline;
            margin-right: 10px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            padding: 5px 10px;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        nav ul li a:hover {
            background-color: #666;
        }

        section {
            padding: 20px;
        }

        footer {
            background-color: #333;
            color: #fff;
            padding: 10px;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .button {
            display: inline-block;
            background-color: #007bff;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            text-decoration: none;
            transition: background-color 0.3s;
        }

        .button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <header>
        <h1>More Advanced Website</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#" id="homeLink">Home</a></li>
            <li><a href="#" id="aboutLink">About</a></li>
            <li><a href="#" id="servicesLink">Services</a></li>
            <li><a href="#" id="contactLink">Contact</a></li>
        </ul>
    </nav>
    <section id="mainContent">
        <h2>Welcome to our More Advanced Website!</h2>
        <p>This is a demonstration of a more advanced HTML website with custom styling and interactivity.</p>
        <button class="button" id="showMessageBtn">Show Message</button>
        <div id="message" style="display: none;">
            <p>This is a hidden message. You can reveal it by clicking the button above.</p>
        </div>
    </section>
    <footer>
        <p>&copy; 2024 More Advanced Website. All rights reserved.</p>
    </footer>

    <script>
        // Advanced JavaScript for interactivity
        document.getElementById('showMessageBtn').addEventListener('click', function() {
            var messageDiv = document.getElementById('message');
            if (messageDiv.style.display === 'none') {
                messageDiv.style.display = 'block';
            } else {
                messageDiv.style.display = 'none';
            }
        });
    </script>
</body>
</html>
