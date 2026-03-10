<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Bank Support</title>
<style>
body{font-family:Arial,Helvetica,sans-serif;margin:0;background:#f4f6f8}
header{background:#0a3d62;color:white;padding:20px;text-align:center}
.container{max-width:900px;margin:auto;padding:20px}
.card{background:white;padding:20px;border-radius:8px;margin-bottom:20px;box-shadow:0 2px 6px rgba(0,0,0,0.1)}
button{background:#0a3d62;color:white;border:none;padding:10px 16px;border-radius:5px;cursor:pointer}
button:hover{opacity:0.9}
input,textarea{width:100%;padding:10px;margin-top:8px;margin-bottom:15px;border:1px solid #ccc;border-radius:5px}
footer{text-align:center;padding:15px;background:#eee}
</style>
</head>
<body>

<header>
<h1>Bank Customer Support</h1>
<p>We are here to help you</p>
</header>

<div class="container">

<div class="card">
<h2>Common Help</h2>
<ul>
<li>Forgot ATM PIN</li>
<li>Block lost debit card</li>
<li>Internet banking problem</li>
<li>Account balance enquiry</li>
</ul>
</div>

<div class="card">
<h2>Contact Support</h2>
<form onsubmit="submitForm(event)">
<label>Name</label>
<input type="text" required>

<label>Email</label>
<input type="email" required>

<label>Your Problem</label>
<textarea required></textarea>

<button type="submit">Submit Request</button>
</form>
<p id="msg" style="color:green"></p>
</div>

<div class="card">
<h2>Support Numbers</h2>
<p>Customer Care: 1800-000-000</p>
<p>Email: support@bank.com</p>
</div>

</div>

<footer>
<p>© 2026 Bank Support. All rights reserved.</p>
</footer>

<script>
function submitForm(e){
 e.preventDefault();
 document.getElementById('msg').innerText='Your request has been submitted. Our team will contact you soon.';
}
</script>

</body>
</html>
