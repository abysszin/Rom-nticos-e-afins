<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pra Nick, minha fofa disfarçada ❤️</title>
    <style>
        body {
            background-color: #ffe6f0;
            font-family: 'Comic Sans MS', cursive, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            overflow: hidden;
            margin: 0;
        }

        .card {
            background: white;
            padding: 30px;
            border-radius: 20px;
            box-shadow: 0 8px 20px rgba(0,0,0,0.2);
            text-align: center;
            position: relative;
            max-width: 500px;
        }

        h1 {
            color: #ff3366;
            margin-bottom: 10px;
        }

        p {
            color: #333;
            font-size: 18px;
            line-height: 1.6;
        }

        .heart {
            color: #ff3366;
            font-size: 30px;
            animation: pulse 1s infinite;
        }

        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.3); }
            100% { transform: scale(1); }
        }

        .button {
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #ff3366;
            color: white;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            font-size: 16px;
            transition: background-color 0.3s ease;
        }

        .button:hover {
            background-color: #e62e5c;
        }

        /* Corações flutuando */
        .hearts {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            overflow: hidden;
            pointer-events: none;
        }

        .hearts span {
            position: absolute;
            display: block;
            color: #ff99cc;
            font-size: 20px;
            animation: float 6s linear infinite;
            opacity: 0.8;
        }

        @keyframes float {
            0% {
                transform: translateY(100vh) translateX(0);
                opacity: 0;
            }
            50% {
                opacity: 1;
            }
            100% {
                transform: translateY(-10vh) translateX(50px);
                opacity: 0;
            }
        }
    </style>
</head>
<body>

    <div class="card">
        <h1>Pra Nick... Minha Fofa (Que Se Faz de Durona) 💖</h1>
        <p>
            Ei, Nick...<br><br>
            Eu sei, você vai dizer que é durona, que não é dessas coisas melosas...<br>
            Mas deixa eu te contar um segredo... <strong>Você é MUITO fofa, sim!</strong> 😍<br><br>
            Você tenta disfarçar, faz cara séria, responde com aquela marra... <br>
            Mas no fundo, eu sei que tem um coração enorme aí dentro. 💗<br><br>
            E quer saber? Eu acho isso a coisa mais linda do mundo. ✨<br>
            Só queria te lembrar o quanto você é incrível, especial e, sim, <strong>MINHA FOFA PREFERIDA!</strong> 💕
        </p>
        <div class="heart">💖</div>
        <button class="button" onclick="alert('Admite vai... você é fofa SIM, Nick! 😍💕')">
            Clica aqui, se tiver coragem 😏
        </button>
        <div class="hearts">
            <span style="left: 10%;">💗</span>
            <span style="left: 20%;">💖</span>
            <span style="left: 30%;">💝</span>
            <span style="left: 40%;">💘</span>
            <span style="left: 50%;">💓</span>
            <span style="left: 60%;">💞</span>
            <span style="left: 70%;">💟</span>
            <span style="left: 80%;">💕</span>
            <span style="left: 90%;">❣️</span>
        </div>
    </div>

</body>
</html>
