<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ORCA Football Club</title>
    <style>
        /* Global Styles */
        body {
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #ffffff;
            color: #333;
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        /* Header */
        header {
            background-color: #4B0082; /* Deep Purple */
            color: white;
            padding: 20px 40px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header h1 {
            font-size: 2em;
            margin: 0;
        }

        nav a {
            margin-left: 20px;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #DA70D6; /* Light Purple */
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(75,0,130,0.7), rgba(75,0,130,0.7)), url('https://images.unsplash.com/photo-1517649763962-0c623066013b?auto=format&fit=crop&w=1950&q=80') center/cover no-repeat;
            height: 70vh;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
        }

        .hero h2 {
            font-size: 3em;
            margin: 0;
        }

        /* About Section */
        .about {
            padding: 60px 40px;
            text-align: center;
        }

        .about h2 {
            color: #4B0082;
            margin-bottom: 20px;
        }

        .about p {
            max-width: 800px;
            margin: auto;
            line-height: 1.6;
        }

        /* Team Section */
        .team {
            background-color: #F5F5F5;
            padding: 60px 40px;
            text-align: center;
        }

        .team h2 {
            color: #4B0082;
            margin-bottom: 40px;
        }

        .players {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 30px;
        }

        .player {
            background-color: white;
            border-radius: 10px;
            padding: 20px;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .player:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.2);
        }

        .player img {
            width: 100%;
            border-radius: 10px;
        }

        .player h3 {
            margin: 15px 0 5px 0;
            color: #4B0082;
        }

        /* Footer */
        footer {
            background-color: #4B0082;
            color: white;
            padding: 20px 40px;
            text-align: center;
        }

        footer a {
            color: #DA70D6;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>ORCA FC</h1>
        <nav>
            <a href="#about">About</a>
            <a href="#team">Team</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <h2>Welcome to ORCA Football Club</h2>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <h2>About Us</h2>
        <p>ORCA Football Club is dedicated to developing talented football players and promoting teamwork, discipline, and sportsmanship. Our club provides training, matches, and community engagement for football enthusiasts of all ages. Join us to be part of a club that values passion, performance, and pride in every game.</p>
    </section>

    <!-- Team Section -->
    <section id="team" class="team">
        <h2>Meet Our Players</h2>
        <div class="players">
            <div class="player">
                <img src="https://images.unsplash.com/photo-1509228627152-000f97dcae8b?auto=format&fit=crop&w=400&q=80
