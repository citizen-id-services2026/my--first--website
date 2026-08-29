<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>मेरी पहली वेबसाइट</title>

    <style><script>
function sendMessage(event) {
    event.preventDefault();
    alert("धन्यवाद! आपका संदेश प्राप्त हुआ 😊");
}
</script>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            background: #f5f7fa;
        }

        header {
            background: #2563eb;
            color: white;
            padding: 40px 20px;
        }

        h1 {
            font-size: 40px;
        }

        nav {
            background: #111827;
            padding: 15px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }

        nav a:hover {
            color: #60a5fa;
        }

        .content {
            padding: 40px 20px;
        }

        section {
            padding: 40px 20px;
            margin: 20px 0;
        }

        button {
            background: #2563eb;
            color: white;
            border: none;
            padding: 14px 25px;
            font-size: 18px;
            border-radius: 8px;
            cursor: pointer;
        }

        button:hover {
            background: #1d4ed8;
        }

        footer {
            margin-top: 50px;
            padding: 20px;
            background: #111827;
            color: white;
        }
    </style>
</head>

<body>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>

    <header id="home">
        <h1>नमस्ते! 👋</h1>
        <p>मेरी पहली वेबसाइट में आपका स्वागत है</p>
    </header>

    <div class="content">

    <h2>मेरे बारे में 👨‍💻</h2>

    <p>
        नमस्ते! मेरा नाम Subhash है।
        यह मेरी पहली वेबसाइट है।
        मैं वेब डिजाइन और टेक्नोलॉजी सीख रहा हूँ।
    </p>

    <h2>मेरी रुचियाँ 🚀</h2>

    <p>
        💻 Web Development
        📱 Technology
        🌐 Internet
    </p>

    <button onclick="showMessage()">
        मुझसे जुड़ें
    </button>

</div>
    
<section id="contact">
    <h2>मुझसे संपर्क करें 📩</h2>

    <form onsubmit="sendMessage(event)">
        <input type="text" placeholder="आपका नाम" required>
        <br><br>

        <input type="email" placeholder="आपका ईमेल" required>
        <br><br>

        <textarea placeholder="अपना संदेश लिखें" rows="5" required></textarea>
        <br><br>

        <button type="submit">संदेश भेजें</button>
    </form>
</section>
    <section id="services">
        <h2>Services</h2>
        <p>मैं यहाँ अपनी सेवाओं की जानकारी दूँगा।</p>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>ईमेल: example@gmail.com</p>
    </section>

    <footer>
        © 2026 मेरी वेबसाइट
    </footer>

    <script>
        function showMessage() {
            alert("नमस्ते! मेरी वेबसाइट पर आपका स्वागत है 😊");
        }
    </script>

</body>
</html>
