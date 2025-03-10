<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Smart Bengaluru - Citizen Engagement</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f2f5;
            color: black;
            text-align: center;
            scroll-behavior: smooth;
        }

        .container {
            max-width: 1200px;
            margin: auto;
            padding: 20px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }
        
        nav {
            background-color: #0073e6;
            padding: 15px;
            color: white;
            text-align: center;
            font-size: 22px;
            font-weight: bold;
            animation: fadeIn 1s forwards;
        }

        .section {
            background-color: #f8f8f8;
            padding: 25px;
            margin: 20px 0;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease-in-out;
        }

        .section:hover {
            transform: scale(1.02);
        }
        
        .dashboard-links {
            display: flex;
            justify-content: space-around;
            margin: 20px 0;
        }

        .dashboard-links a {
            background-color: #0073e6;
            color: white;
            padding: 15px;
            border-radius: 10px;
            text-decoration: none;
            font-weight: bold;
            transition: background-color 0.3s ease-in-out;
        }

        .dashboard-links a:hover {
            background-color: #005bb5;
        }
    </style>
</head>
<body>
    <div class="container">
        <nav>
            <h1>Smart Bengaluru - Citizen Engagement Platform</h1>
        </nav>
        
        <div class="dashboard-links">
            <a href="#civic-issues">Report an Issue</a>
            <a href="#complaint-tracking">Track Complaint</a>
            <a href="#sustainability-challenges">Join Sustainability</a>
            <a href="#pollution-monitoring">Pollution Data</a>
            <a href="#collaboration">Government & NGO Collaboration</a>
        </div>
        
        <section class="section" id="civic-issues">
            <h2>Report an Issue</h2>
            <form>
                <input type="text" placeholder="Issue Title" required>
                <textarea placeholder="Describe the issue" required></textarea>
                <input type="file" accept="image/*">
                <input type="text" placeholder="Location" required>
                <button type="submit">Submit Issue</button>
            </form>
        </section>
        
        <section class="section" id="complaint-tracking">
            <h2>Track Complaints</h2>
            <p>Enter your complaint ID to check the status.</p>
            <input type="text" placeholder="Complaint ID" required>
            <button>Track</button>
        </section>
        
        <section class="section" id="sustainability-challenges">
            <h2>Join Sustainability Initiatives</h2>
            <p>Participate in green programs and eco-friendly activities.</p>
            <button>Join Now</button>
        </section>
        
        <section class="section" id="pollution-monitoring">
            <h2>Live Pollution & Infrastructure Data</h2>
            <p>Monitor real-time air and water quality data.</p>
            <button>View Data</button>
        </section>
        
        <section class="section" id="collaboration">
            <h2>Government & NGO Collaboration</h2>
            <p>Engage with local authorities and NGOs to improve Bengaluru.</p>
            <button>Explore Initiatives</button>
        </section>
    </div>
</body>
</html>
