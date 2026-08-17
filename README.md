<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blackout City - Home</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        body {
            background-color: #0b0b0b;
            color: #ffffff;
            overflow-x: hidden;
        }
        nav {
            display: flex;
            justify-content: center;
            gap: 30px;
            padding: 20px;
            background: rgba(0,0,0,0.8);
            border-bottom: 1px solid #222;
        }
        nav a {
            color: #aaa;
            text-decoration: none;
            font-size: 13px;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 1px;
            transition: 0.2s;
        }
        nav a:hover, nav a.active {
            color: #fff;
            border-bottom: 2px solid #e71d36;
            padding-bottom: 2px;
        }
        .header-container {
            text-align: center;
            padding: 50px 20px 30px;
        }
        h1 {
            font-size: 38px;
            text-transform: uppercase;
            font-weight: 900;
            letter-spacing: 2px;
            margin-bottom: 10px;
        }
        h1 span.blackout {
            color: #ffffff;
        }
        h1 span.app {
            color: #e71d36;
        }
        p.subtitle {
            color: #888;
            font-size: 13px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        .cards-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 20px;
            max-width: 1200px;
            margin: 30px auto;
            padding: 0 20px;
        }
        .card {
            background: linear-gradient(to bottom, rgba(20,20,20,0.7), rgba(10,10,10,0.9)), url('https://images.unsplash.com/photo-1514565131-fce0801e5785?auto=format&fit=crop&w=500&q=80');
            background-size: cover;
            background-position: center;
            border: 1px solid #222;
            border-radius: 6px;
            height: 250px;
            padding: 25px;
            display: flex;
            flex-direction: column;
            justify-content: flex-end;
            text-decoration: none;
            transition: transform 0.3s, border-color 0.3s;
        }
        .card:hover {
            transform: translateY(-5px);
            border-color: #e71d36;
        }
        .card-icon {
            font-size: 24px;
            margin-bottom: auto;
            color: #fff;
        }
        .card-title {
            color: #fff;
            font-size: 15px;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
    </style>
</head>
<body>

    <nav>
        <a href="index.html" class="active">Home</a>
        <a href="#">Events</a>
        <a href="#">Rules</a>
        <a href="apply.html">Applications</a>
        <a href="#">Team</a>
        <a href="#">Streamers</a>
    </nav>

    <div class="header-container">
        <h1><span class="blackout">BLACKOUT CITY</span> <span class="app">APPLICATIONS</span></h1>
        <p class="subtitle">Select a department to submit your official application directly to our team</p>
    </div>

    <div class="cards-grid">
        <a href="apply.html" class="card">
            <div class="card-icon">👤</div>
            <div class="card-title">Whitelist (Citizen)</div>
        </a>
        <a href="apply.html" class="card">
            <div class="card-icon">🛡️</div>
            <div class="card-title">Gang & Family</div>
        </a>
        <a href="apply.html" class="card">
            <div class="card-icon">⭐</div>
            <div class="card-title">Police Department</div>
        </a>
        <a href="apply.html" class="card">
            <div class="card-icon">✚</div>
            <div class="card-title">EMS Department</div>
        </a>
    </div>

</body>
</html>
