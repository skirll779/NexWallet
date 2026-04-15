<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>NexWallet</title>

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #0b1220;
  color: white;
}

/* NAVBAR */
.navbar {
  display: flex;
  justify-content: space-between;
  padding: 20px 40px;
  background: #0f1a2e;
  align-items: center;
}

.logo {
  font-size: 22px;
  font-weight: bold;
  color: #00d4ff;
}

/* HERO */
.hero {
  text-align: center;
  padding: 80px 20px;
}

.hero h1 {
  font-size: 50px;
  margin-bottom: 10px;
}

.hero p {
  color: #a1a1aa;
  font-size: 18px;
}

.btn {
  margin-top: 20px;
  padding: 12px 25px;
  background: #00d4ff;
  border: none;
  border-radius: 8px;
  color: black;
  font-weight: bold;
  cursor: pointer;
}

/* CARDS */
.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
  padding: 40px;
}

.card {
  background: #111c33;
  padding: 20px;
  border-radius: 12px;
  border: 1px solid #1f2a44;
}

.card h3 {
  color: #00d4ff;
}

/* FOOTER */
footer {
  text-align: center;
  padding: 20px;
  color: #777;
  margin-top: 30px;
}
</style>

</head>

<body>

<div class="navbar">
  <div class="logo">🚀 NexWallet</div>
  <div>Login | Register</div>
</div>

<div class="hero">
  <h1>Secure Digital Wallet</h1>
  <p>Send, receive and manage your digital assets in one place.</p>
  <button class="btn">Get Started</button>
</div>

<div class="cards">
  <div class="card">
    <h3>⚡ Fast Transfers</h3>
    <p>Send money instantly anywhere in the world.</p>
  </div>

  <div class="card">
    <h3>🔐 Secure</h3>
    <p>Your funds are protected with modern security.</p>
  </div>

  <div class="card">
    <h3>📊 Dashboard</h3>
    <p>Track your balance and activity in real time.</p>
  </div>

  <div class="card">
    <h3>🌍 Global</h3>
    <p>Access your wallet from anywhere, anytime.</p>
  </div>
</div>

<footer>
  © 2026 NexWallet. All rights reserved.
</footer>

</body>
</html>
