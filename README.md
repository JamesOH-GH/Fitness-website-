# Fitness-website-
fitness-website/
├── index.html
├── styles.css
├── script.js
└── images/
    └── logo.png

    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fitness Plan</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="images/logo.png" alt="Fitness Plan Logo" class="logo">
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="fitness-plan.html">Fitness Plan</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="hero">
            <h1>Welcome to Your Fitness Journey</h1>
            <p>Get fit, stay healthy, and transform your life with our customized fitness plans.</p>
            <a href="fitness-plan.html" class="btn">Get Started</a>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Fitness Plan. All rights reserved.</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>


body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    background-color: #333;
    color: white;
    padding: 10px 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    height: 50px;
}

nav ul {
    list-style-type: none;
    display: flex;
    gap: 20px;
}

nav ul li {
    display: inline;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

.hero {
    background: url('images/hero-bg.jpg') no-repeat center center/cover;
    height: 80vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: white;
}

.hero h1 {
    font-size: 3em;
    margin-bottom: 10px;
}

.hero p {
    font-size: 1.5em;
    margin-bottom: 20px;
}

.btn {
    background-color: #e63946;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    font-size: 1.2em;
    border-radius: 5px;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
}


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fitness Plan</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="images/logo.png" alt="Fitness Plan Logo" class="logo">
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="fitness-plan.html">Fitness Plan</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="plan">
            <h1>Our Fitness Plan</h1>
            <p>Our fitness plan includes personalized workouts, nutrition advice, and continuous support to help you achieve your goals.</p>
            <div class="workout-plan">
                <h2>Week 1</h2>
                <ul>
                    <li>Day 1: Full Body Workout</li>
                    <li>Day 2: Cardio and Core</li>
                    <li>Day 3: Upper Body Strength</li>
                    <li>Day 4: Rest</li>
                    <li>Day 5: Lower Body Strength</li>
                    <li>Day 6: Cardio and Core</li>
                    <li>Day 7: Rest</li>
                </ul>
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Fitness Plan. All rights reserved.</p>
    </footer>
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="images/logo.png" alt="Fitness Plan Logo" class="logo">
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="fitness-plan.html">Fitness Plan</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="contact">
            <h1>Contact Us</h1>
            <form action="#" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="4" required></textarea>

                <button type="submit" class="btn">Send</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Fitness Plan. All rights reserved.</p>
    </footer>
</body>
</html>


// script.js
document.addEventListener('DOMContentLoaded', () => {
    console.log('Fitness Plan website loaded');
});
