<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TankLegends Market</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>TankLegends Market</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Accounts</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="accounts">
            <h2>Available Accounts</h2>
            <div class="account-list">
                <div class="account-item">
                    <h3>Elite Commander</h3>
                    <p>Level: 50</p>
                    <p>Price: $70</p>
                    <button onclick="buyAccount('Elite Commander')">Buy Now</button>
                </div>
                <div class="account-item">
                    <h3>Battle Veteran</h3>
                    <p>Level: 40</p>
                    <p>Price: $60</p>
                    <button onclick="buyAccount('Battle Veteran')">Buy Now</button>
                </div>
                <div class="account-item">
                    <h3>New Recruit</h3>
                    <p>Level: 30</p>
                    <p>Price: $50</p>
                    <button onclick="buyAccount('New Recruit')">Buy Now</button>
                </div>
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 TankLegends Market</p>
    </footer>
    <script src="scripts.js"></script>
</body>
</html>
