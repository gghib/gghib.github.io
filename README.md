<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First HTML Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 10px;
            background-color: #f4f4f9;
        }
        header {
            background: #333;
            color: #fff;
            padding: 10px 20px;
            text-align: center;
        }
        img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
        }
        a {
            color: #007bff;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to My Website</h1>
        <p>This is a sample HTML page</p>
    </header>

    <main>
        <section>
            <h2>About Me</h2>
            <p>Hello! I am learning HTML and front-end development. This is my first simple website built using HTML!</p>
        </section>

        <section>
            <h2>My Favorite Image</h2>
            <p>Here is one of my favorite images:</p>
            <img src="https://www.example.com/myimage.jpg" alt="Sample Image">
        </section>

        <section>
            <h2>More Information</h2>
            <p>Visit the following link for more information:</p>
            <a href="https://www.example.com" target="_blank">Click Here</a>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 My Name | This website is for learning purposes only</p>
    </footer>

</body>
</html>
