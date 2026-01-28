<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cortex Network | Kalite Burada</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700;900&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0; padding: 0; font-family: 'Poppins', sans-serif;
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://wallpaperaccess.com/full/466333.jpg');
            background-size: cover; background-attachment: fixed; background-position: center;
            color: white; height: 100vh; display: flex; flex-direction: column; align-items: center; justify-content: center;
        }
        .container { text-align: center; backdrop-filter: blur(10px); padding: 50px; border-radius: 30px; border: 1px solid rgba(255,255,255,0.1); background: rgba(0,0,0,0.4); }
        .logo { font-size: 70px; font-weight: 900; letter-spacing: 5px; margin-bottom: 10px; background: linear-gradient(to right, #8A2BE2, #00FFFF); -webkit-background-clip: text; -webkit-text-fill-color: transparent; drop-shadow: 0 0 20px rgba(138, 43, 226, 0.5); }
        .sub-text { font-size: 18px; letter-spacing: 2px; color: #ccc; margin-bottom: 30px; text-transform: uppercase; }
        .ip-box { background: rgba(255,255,255,0.1); padding: 15px 30px; border-radius: 50px; border: 2px solid #00FFFF; font-weight: bold; font-size: 20px; transition: 0.3s; cursor: pointer; display: inline-block; }
        .ip-box:hover { background: #00FFFF; color: black; box-shadow: 0 0 30px #00FFFF; }
        .links { margin-top: 30px; }
        .btn { text-decoration: none; color: white; margin: 0 15px; font-weight: bold; padding: 10px 20px; border-radius: 5px; background: #8A2BE2; transition: 0.3s; }
        .btn:hover { background: #6a1b9a; transform: translateY(-3px); }
    </style>
</head>
<body>

    <div class="container">
        <div class="logo">CORTEX</div>
        <div class="sub-text">Sıradanlığın Ötesinde Bir Deneyim</div>
        
        <div class="ip-box" onclick="copyIP()">PLAY.CORTEXNETWORK.COM</div>
        
        <div class="links">
            <a href="#" class="btn">MAĞAZA</a>
            <a href="#" class="btn" style="background: #7289da;">DISCORD</a>
            <a href="#" class="btn" style="background: #2ecc71;">KAYIT OL</a>
        </div>
    </div>

    <script>
        function copyIP() {
            navigator.clipboard.writeText("play.cortexnetwork.com");
            alert("Sunucu IP adresi kopyalandı! İyi oyunlar.");
        }
    </script>

</body>
</html>
