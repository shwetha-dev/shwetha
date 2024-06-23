<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            color: #333;
        }
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0px 0px 10px 0px rgba(0,0,0,0.1);
        }
        footer {
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
            background-color: #333;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Simple Webpage</h1>
        <p>Enjoy your visit!</p>
    </header>

    <div class="container">
        <section>
            <h2>About Me</h2>
            <p>I am creating this webpage to learn HTML.</p>
        </section>
        <section>
            <h2>My Interests</h2>
            <ul>
                <li>Reading</li>
                <li>Writing</li>
                <li>Playing guitar</li>
            </ul>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Simple Webpage. All rights reserved.</p>
    </footer>
</body>
</html>
