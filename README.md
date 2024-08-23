<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Watermelon - Raising Money for Palestine!</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffffff;
            color: #333333;
        }
        header {
            background-color: #000000;
            color: #ffffff;
            padding: 20px;
            text-align: center;
            border-bottom: 10px solid #FF0000;
        }
        header h1 {
            margin: 0;
        }
        header p {
            font-size: 18px;
            margin: 5px 0 0;
        }
        .content {
            padding: 20px;
            max-width: 800px;
            margin: 0 auto;
        }
        section {
            margin-bottom: 40px;
        }
        h2 {
            color: #008000;
            border-bottom: 2px solid #FF0000;
            padding-bottom: 10px;
        }
        .watermelon-border {
            border: 10px solid #008000;
            background-image: url('https://example.com/path-to-watermelon-image.jpg');
            background-size: 50px 50px;
            padding: 20px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        footer {
            background-color: #000000;
            color: #ffffff;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        a {
            color: #FF0000;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        form {
            max-width: 400px;
            margin: 20px 0;
            background-color: #f9f9f9;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        form label {
            display: block;
            margin-bottom: 10px;
            font-weight: bold;
        }
        form input[type="text"],
        form input[type="number"] {
            width: calc(100% - 22px);
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        form input[type="submit"] {
            background-color: #008000;
            color: #ffffff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        form input[type="submit"]:hover {
            background-color: #006400;
        }
        .disclaimer {
            font-size: 12px;
            color: #666666;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>The Watermelon</h1>
        <p>Raising Money for Palestine!</p>
    </header>

    <div class="content watermelon-border">
        <section id="about">
            <h2>About Me</h2>
            <p>Welcome to The Watermelon, a platform dedicated to raising awareness and funds for the Palestinian cause. Our mission is to support the people of Palestine through various charitable initiatives and events. Join us in making a difference!</p>
        </section>

        <section id="causes">
            <h2>Causes Supported</h2>
            <p>We are committed to supporting a variety of causes that provide aid to those in need in Palestine. From food and medical supplies to educational resources, your contributions help us make a significant impact. Learn more about the specific initiatives we support.</p>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>If you have any questions or would like to get involved, please reach out to us:</p>
            <ul>
                <li>Email: <a href="mailto:contact@thewatermelon.com">contact@thewatermelon.com</a></li>
                <li>Phone: +123 456 7890</li>
                <li>Social Media: <a href="#">Facebook</a> | <a href="#">Twitter</a> | <a href="#">Instagram</a></li>
            </ul>
        </section>

        <section id="donate">
            <h2>Donate</h2>
            <p>Your contributions are crucial to our mission. Every donation, big or small, helps us provide essential aid to those in need. Please fill out the form below to donate.</p>
            <form action="#" method="POST">
                <label for="cc-number">Credit Card Number:</label>
                <input type="text" id="cc-number" name="cc-number" placeholder="1234-5678-9123-4567" required>

                <label for="name">Name (Optional):</label>
                <input type="text" id="name" name="name" placeholder="Your Name">

                <label for="amount">Donation Amount (USD):</label>
                <input type="number" id="amount" name="amount" min="1" required>

                <input type="submit" value="Donate Now">
            </form>
            <p class="disclaimer">Your information is securely processed and will never be used for anything else.</p>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 The Watermelon - All Rights Reserved</p>
    </footer>
</body>
</html>
