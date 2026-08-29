<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Citizen ID Services</title>

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f2f5f8;
            color: #222;
        }

        header {
            background: #1769aa;
            color: white;
            text-align: center;
            padding: 25px 15px;
        }

        header h1 {
            margin: 0;
            font-size: 30px;
        }

        header p {
            margin-bottom: 0;
        }

        .container {
            max-width: 900px;
            margin: auto;
            padding: 20px;
        }

        .welcome {
            background: white;
            padding: 25px;
            border-radius: 12px;
            text-align: center;
            margin-bottom: 20px;
        }

        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 15px;
        }

        .card {
            background: white;
            padding: 20px;
            border-radius: 12px;
            text-align: center;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
        }

        .card h3 {
            margin-top: 5px;
        }

        button {
            background: #1769aa;
            color: white;
            border: none;
            padding: 10px 18px;
            border-radius: 7px;
            cursor: pointer;
            font-size: 15px;
        }

        button:hover {
            opacity: 0.9;
        }

        footer {
            margin-top: 30px;
            background: #222;
            color: white;
            text-align: center;
            padding: 18px;
        }
    </style>
</head>

<body>

<header>
    <h1>🪪 Citizen ID Services</h1>
    <p>नागरिक सेवाओं के लिए आपका ऑनलाइन पोर्टल</p>
</header>

<div class="container">

    <div class="welcome">
        <h2>स्वागत है! 👋</h2>
        <p>यहाँ आपको नागरिक सेवाओं की जानकारी आसानी से मिलेगी।</p>
    </div>

    <h2>हमारी सेवाएँ</h2>

    <div class="services">

        <div class="card">
            <h3>🪪 पहचान पत्र</h3>
            <p>पहचान संबंधी सेवाओं की जानकारी</p>
            <button onclick="showMessage('पहचान पत्र सेवा चुनी गई')">
                देखें
            </button>
        </div>

        <div class="card">
            <h3>📄 प्रमाण पत्र</h3>
            <p>विभिन्न प्रमाण पत्रों की जानकारी</p>
            <button onclick="showMessage('प्रमाण पत्र सेवा चुनी गई')">
                देखें
            </button>
        </div>

        <div class="card">
            <h3>📝 आवेदन</h3>
            <p>ऑनलाइन आवेदन संबंधी जानकारी</p>
            <button onclick="showMessage('आवेदन सेवा चुनी गई')">
                देखें
            </button>
        </div>

        <div class="card">
            <h3>📞 संपर्क</h3>
            <p>सहायता के लिए संपर्क करें</p>
            <button onclick="showMessage('संपर्क पेज जल्द उपलब्ध होगा')">
                संपर्क
            </button>
        </div>

    </div>

</div>

<footer>
    © 2026 Citizen ID Services
</footer>

<script>
    function showMessage(message) {
        alert(message);
    }
</script>

</body>
</html>
