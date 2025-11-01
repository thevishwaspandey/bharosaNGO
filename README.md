# bharosaNGO
Its an ngo where people donate money for needy people
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>HopeRise Foundation – Donate Now</title>
<style>
body {
  font-family: 'Poppins', sans-serif;
  background: #f3f6f9;
  color: #222;
  margin: 0;
  text-align: center;
}
header {
  background: linear-gradient(90deg, #00aaff, #00ffaa);
  color: white;
  padding: 20px 0;
  font-size: 28px;
  font-weight: 600;
}
.container {
  max-width: 700px;
  margin: 40px auto;
  background: white;
  padding: 30px;
  border-radius: 16px;
  box-shadow: 0 0 20px rgba(0,0,0,0.1);
}
h2 {
  color: #0077cc;
}
button {
  background: linear-gradient(90deg, #00aaff, #00ffaa);
  border: none;
  color: white;
  font-size: 18px;
  padding: 12px 25px;
  border-radius: 10px;
  cursor: pointer;
  transition: 0.3s;
}
button:hover {
  transform: scale(1.1);
}
.qr img {
  width: 200px;
  height: 200px;
  margin-top: 15px;
  border: 5px solid #eee;
  border-radius: 12px;
}
footer {
  margin-top: 50px;
  font-size: 14px;
  color: #555;
}
</style>
</head>
<body>

<header>🌿 HopeRise Foundation 🌿</header>

<div class="container">
  <h2>Make a Difference Today 💙</h2>
  <p>
    HopeRise Foundation works to provide food, education, and healthcare
    to underprivileged children and families across India.
    Your small donation can change a life!
  </p>

  <h3>Donate via UPI</h3>
  <p>Use our official UPI ID: <strong>your-ngo-upi@bank</strong></p>
  <div class="qr">
    <img src="https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=upi://pay?pa=your-ngo-upi@bank&pn=HopeRiseFoundation" alt="UPI QR Code">
  </div>
  <br>
  <button onclick="window.open('upi://pay?pa=your-ngo-upi@bank&pn=HopeRiseFoundation')">Donate Now</button>
</div>

<footer>
  © 2025 HopeRise Foundation | Registered NGO | All rights reserved
</footer>

</body>
</html>

