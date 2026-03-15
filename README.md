# haha-so-embarrassing
nothing 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Analytics Dashboard</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>📊 Real-time Analytics Dashboard</h1>
        
        <div class="stats-grid">
            <div class="stat-card">
                <h3>Total Visits</h3>
                <div class="stat-number" id="totalVisits">0</div>
            </div>
            <div class="stat-card">
                <h3>Unique Visitors</h3>
                <div class="stat-number" id="uniqueVisitors">0</div>
            </div>
            <div class="stat-card">
                <h3>Today</h3>
                <div class="stat-number" id="todayVisits">0</div>
            </div>
            <div class="stat-card">
                <h3>Avg Session Time</h3>
                <div class="stat-number" id="avgSession">0s</div>
            </div>
        </div>

        <div class="recent-visits">
            <h3>Recent Visitors</h3>
            <div id="visitorsList"></div>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
