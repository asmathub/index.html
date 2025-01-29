<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>I'm Sorry Dear Monika</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-image: url('https://images.unsplash.com/photo-1512442022020-1c1e1c1e1c1e?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=MnwxMTc3M3wwfDF8c2VhcmNofDF8fGZsb3dlcnxlbnwwfHx8fDE2MzYyMjY0MjA&ixlib=rb-1.2.1&q=80&w=1080'); /* Floral background */
            background-size: cover;
            background-position: center;
            overflow: hidden;
        }

        @keyframes backgroundAnimation {
            0% {
                filter: brightness(1);
            }
            100% {
                filter: brightness(0.8);
            }
        }

        h1 {
            font-size: 48px;
            color: #4b0082; /* Indigo color */
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
            animation: textAnimation 1s ease-in-out infinite alternate; /* Faster animation */
        }

        @keyframes textAnimation {
            0% {
                transform: translateY(0);
            }
            100% {
                transform: translateY(-10px);
            }
        }

        .highlight {
            color: #ff4500; /* OrangeRed color */
            font-weight: bold;
        }

        .heart {
            font-size: 48px; /* Heart emoji size */
            margin-top: 20px; /* Space between text and heart */
        }

        /* Balloon Animation */
        .balloon {
            position: absolute;
            bottom: -100px;
            animation: float 5s infinite;
            opacity: 0.7;
        }

        @keyframes float {
            0% {
                transform: translateY(0);
            }
            100% {
                transform: translateY(-100vh);
            }
        }
    </style>
</head>
<body>
    <h1>I'm sorry dear <span class="highlight">Monika</span>, love of my life</h1>
    <div class="heart">❤️</div>

    <!-- Balloon Images -->
    <img src="https://img.icons8.com/color/48/000000/balloon.png" class="balloon" style="left: 10%; animation-delay: 0s;">
    <img src="https://img.icons8.com/color/48/000000/balloon.png" class="balloon" style="left: 30%; animation-delay: 1s;">
    <img src="https://img.icons8.com/color/48/000000/balloon.png" class="balloon" style="left: 50%; animation-delay: 2s;">
    <img src="https://img.icons8.com/color/48/000000/balloon.png" class="balloon" style="left: 70%; animation-delay: 3s;">
    <img src="https://img.icons8.com/color/48/000000/balloon.png" class="balloon" style="left: 90%; animation-delay: 4s;">
</body>
</html>
