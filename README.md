<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TransHookup ✅️</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<header>
    <img src="your_uploaded_logo.png" alt="TransHookup Logo">
    <h1>TransHookup ✅️</h1>
</header>

<div class="container">
    <button class="hookup-btn" onclick="startScan()">🔥 Hookup Now</button>
    
    <p class="scan-message" id="scanMessage">🔍 Scanning for trans people near you...</p>

    <div class="result-container" id="result">
        <h3>✅ Match Found Near <span id="userLocation">You</span>!</h3>
        <p><strong>📞 <span id="phoneNumber">+1 (817) 489-3976</span></strong></p>
        <p>💬 Text this private number on <strong>WhatsApp</strong></p>
        <p class="warning">⚠️ Do NOT share this number privately and NO cash payment!</p>
        
        <p class="naughty-text">🔥 Ready for some wild fun? Don't hold back! 😏</p>
        <p class="caution">⚠️ Stay safe and use protection. Your well-being matters!</p>
    </div>
</div>

<script>
    function startScan() {
        document.getElementById("scanMessage").style.display = "block";
        document.getElementById("result").style.display = "none";

        setTimeout(() => {
            document.getElementById("scanMessage").style.display = "none";
            document.getElementById("result").style.display = "block";
        }, 3000);
    }
</script>

</body>
</html>
/* General Styles */
body {
    font-family: Arial, sans-serif;
    text-align: center;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
}

/* Header */
header {
    background: linear-gradient(45deg, #55CDFC, #F7A8B8);
    color: white;
    padding: 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
}

header img {
    width: 120px;
    margin-bottom: 10px;
}

h1 {
    font-size: 28px;
}

/* Main Content */
.container {
    margin-top: 50px;
}

/* Button */
.hookup-btn {
    background: #FF4D79;
    color: white;
    padding: 15px 30px;
    border: none;
    font-size: 20px;
    border-radius: 8px;
    cursor: pointer;
    transition: 0.3s;
}

.hookup-btn:hover {
    background: #ff2f63;
}

/* Scanning & Results */
.scan-message {
    display: none;
    font-size: 18px;
    color: #333;
    margin-top: 20px;
}

.result-container {
    display: none;
    background: white;
    padding: 20px;
    width: 300px;
    margin: auto;
    border-radius: 5px;
    box-shadow: 0px 0px 10px gray;
}

.warning {
    color: red;
    font-weight: bold;
    margin-top: 10px;
}

.naughty-text {
    color: #ff4d79;
    font-style: italic;
    margin-top: 15px;
}

.caution {
    color: black;
    font-weight: bold;
    margin-top: 20px;
}
