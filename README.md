<html lang="hu">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        p{
            color: beige;
            position: relative;
        }
        #bo{
            position: absolute;
            z-index: -1;
            filter: blur(0px);
            width: 15%;
            height: auto;
        }
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background-color: #f0f8ff; /* Világoskék háttér */
            color: #333;
            text-align: center;
        }
        h1 {
            font-size: 4em;
            margin-top: 20px;
            position: relative;
            top: 70px;
            left: -400px;
        }
        .subtitle {
            font-size: 1.5em;
            font-weight: bold;
            margin-top: 10px;
        }
        .description {
            font-size: 1.2em;
            margin: 20px 10%;
        }
        .features {
            position: relative;     
            left: 100px; 
            width: 1000px;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
            margin: 20px 10%;
        }
        .feature-bubble {
            background-color: rgb(76,12,4);
            border: 2px solid #ccc;
            border-radius: 15px;
            padding: 20px;
            font-size: 1.1em;
            width: 200px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .footer-text {
            font-size: 1.5em;
            font-weight: bold;
            margin-top: 30px;
        }
    </style>
</head>
<body>
    <h1>LONGAEVUS</h1>
    <img src="logo.png" id="bo" >
    <div style="height: 100px;"></div>
    <div class="subtitle">Az új otthon, ahol az élet kivirágzik</div>
    <div class="description">
        A Longaevus egy különleges, nyugdíjasok számára kialakított lakópark, amely az elmagányosodás helyett a közösség erejét nyújtja.
        Itt minden adott a teljes gondtalan élethez:
    </div>
    <div class="features">
        <div class="feature-bubble"><p>Esztétikai szolgáltatások</p></div>
        <div class="feature-bubble"><p>Gyógytorna</p></div>
        <div class="feature-bubble"><p>Orvosi ellátás</p></div>
        <div class="feature-bubble"><p>Mozgási lehetőség</p></div>
        <div class="feature-bubble"><p>Segítőkész munkatársak</p></div>
    </div>
    <div class="footer-text">
        NEM CSUPÁN LAKÓHELY - EGY OTTHON, AHOL AZ ÉLETMINŐSÉG ÉS A KÖZÖSSÉG AZ ELSŐ
    </div>
</body>
</html>
