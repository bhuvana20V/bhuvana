<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled HTML Page</title>
    <style>
        /* Basic reset */
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            line-height: 1.6;
        }

        /* Header styling */
        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px 0;
            text-align: center;
        }

        /* Main section styling */
        main {
            padding: 20px;
        }

        h1 {
            color: #333;
            font-size: 2em;
        }

        h2 {
            color: #555;
        }

        /* Unordered list styling */
        ul {
            list-style-type: none;
            padding: 0;
        }

        ul li {
            background-color: #f4f4f4;
            margin: 5px 0;
            padding: 10px;
            border-radius: 5px;
        }

        /* Image styling */
        img {
            max-width: 100%;
            height: auto;
            border: 2px solid #ddd;
            border-radius: 5px;
        }

        /* Footer styling */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        /* Link styling */
        a {
            color: #4CAF50;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Styled Page</h1>
    </header>

    <main>
        <section>
            <h2>About This Page</h2>
            <p>This is a simple example of an HTML document styled with CSS. Below are some images and a list of items.</p>

            <ul>
                <li>First item</li>
                <li>Second item</li>
                <li>Third item</li>
            </ul>

            <img src="https://via.placeholder.com/600x400" alt="Sample Image">
            <img src="https://via.placeholder.com/600x400?text=Another+Image" alt="Another Sample Image">
        </section>
    </main>

    <footer>
        <p>&copy; 2024 My Styled Page</p>
    </footer>
</body>
</html>
