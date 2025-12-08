<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>遺憾故事圖書館</title>
    <style>
        body {
            font-family: 'Georgia', serif;
            background-color: #fafafa;
            color: #333;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        
        h1 {
            text-align: center;
            color: #2c3e50;
        }
        
        h2 {
            text-align: center;
            color: #34495e;
            margin-bottom: 20px;
        }

        .bookshelf {
            display: flex;
            flex-direction: row; 
            justify-content: center; 
            margin-top: 20px;
            flex-wrap: wrap; 
        }

        .book {
            width: 180px;
            height: 100px;
            background-color: #e2d1c3;
            border: 2px solid #b79f8c;
            border-radius: 5px;
            text-align: center;
            padding: 10px;
            transition: transform 0.3s, background-color 0.3s;
            position: relative;
            margin: 10px;
            box-shadow: 3px 3px 8px rgba(0, 0, 0, 0.3);
            perspective: 1000px;
            text-decoration: none; 
            color: inherit; 
            cursor: pointer;
        }

        .book-title {
            font-size: 1.2em;
            font-weight: bold;
            color: #2c3e50;
        }

        .book:before {
            content: '';
            position: absolute;
            top: 0;
            left: -10px;
            width: 20px;
            height: 100%;
            background: linear-gradient(to right, rgba(226, 209, 195, 0.9), rgba(199, 171, 153, 0.9));
            border-left: 2px solid #b79f8c;
            border-radius: 4px 0 0 4px;
        }

        .book:hover {
            transform: rotateY(10deg);
            background-color: #d1b4a1; /* Change color on hover for visual feedback */
        }

        footer {
            margin-top: 20px;
            text-align: center;
            color: #777;
        }
    </style>
</head>
<body>
    <h1>遺憾故事圖書館</h1>
    <h2>A Journey Through Time and Reflection</h2>
    
    <div class="bookshelf">
        <a href="letter1.html" target="_blank" class="book">
            <span class="book-title">October 09 2023</span> 
        </a>
        <a href="letter2.html" target="_blank" class="book">
            <span class="book-title">October 11 2023</span>
        </a>
        <a href="letter3.html" target="_blank" class="book">
            <span class="book-title">December 22 2023</span>
        </a>
        <a href="letter4.html" target="_blank" class="book">
            <span class="book-title">February 24 2023</span>
        </a>
        <a href="letter5.html" target="_blank" class="book">
            <span class="book-title">May 17 2024</span>
        </a>
        <a href="letter6.html" target="_blank" class="book">
            <span class="book-title">June 02 2024</span>
        </a>
        <a href="letter7.html" target="_blank" class="book">
            <span class="book-title">June 09 2024</span>
        </a>
        <a href="letter8.html" target="_blank" class="book">
            <span class="book-title">Augest 02 2024</span>
        </a>
        <a href="letter9.html" target="_blank" class="book">
            <span class="book-title">Augest 03 2024</span>
        </a>
        <a href="letter10.html" target="_blank" class="book">
            <span class="book-title">February 20 2025</span>
        </a>
        <a href="letter11.html" target="_blank" class="book">
            <span class="book-title">September 10 2025</span>
        </a>
        <a href="letter12.html" target="_blank" class="book">
            <span class="book-title">November 27 2025</span>
        </a>
    </div>

    <footer>
        <p>&copy; 2025 遺憾故事圖書館. All Rights Reserved.</p>
    </footer>
</body>
</html>
