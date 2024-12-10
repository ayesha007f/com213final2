<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Hosting Canada</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #005ea2;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        header img {
            max-width: 150px;
        }
        nav {
            background-color: #004a86;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }
        nav a {
            color: white;
            padding: 10px 20px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #003d6a;
        }
        .search-section {
            text-align: center;
            padding: 20px;
            background-color: #e0f3ff;
        }
        .search-section input[type="text"] {
            padding: 10px;
            width: 60%;
            margin-right: 10px;
            border: 1px solid #ccc;
        }
        .search-section button {
            padding: 10px 20px;
            background-color: #005ea2;
            color: white;
            border: none;
            cursor: pointer;
        }
        .hero {
            background: url('https://via.placeholder.com/1200x400') no-repeat center center/cover;
            height: 400px;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 2rem;
        }
        .content-section {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            padding: 20px;
            text-align: center;
        }
        .content-box {
            background-color: white;
            border: 1px solid #ddd;
            padding: 20px;
        }
        footer {
            background-color: #005ea2;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>
    <header>
        <img src="https://via.placeholder.com/150x50" alt="Logo">
        <h1>Web Hosting Canada</h1>
    </header>
    <nav>
        <a href="home.html">Home</a>
        <a href="plans.html">Hosting Plans</a>
        <a href="registration.html">Sign Up</a>
        <a href="login.html">Login</a>
    </nav>
    <div class="search-section">
        <input type="text" placeholder="Search hosting plans...">
        <button>Search</button>
    </div>
    <div class="hero">
        <span>Fast & Reliable Web Hosting Solutions</span>
    </div>
    <div class="content-section">
        <div class="content-box">
            <h2>Affordable Plans</h2>
            <p>Starting at just $3.99/month. Great value hosting!</p>
        </div>
        <div class="content-box">
            <h2>24/7 Support</h2>
            <p>Get expert help whenever you need it.</p>
        </div>
        <div class="content-box">
            <h2>Fast Speed</h2>
            <p>Enjoy ultra-fast website performance.</p>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 Web Hosting Canada | Follow us on social media</p>
    </footer>
</body>
</html>
