<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday Andreas!</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f8ff;
        }

        .container {
            text-align: center;
            font-family: 'Arial', sans-serif;
        }

        .balloons {
            display: flex;
            justify-content: space-around;
            width: 100%;
            height: 200px;
            margin-bottom: 20px;
        }

        .balloon {
            width: 50px;
            height: 70px;
            background-color: lightblue;
            border-radius: 50%;
            animation: float 3s ease-in-out infinite;
        }

        @keyframes float {
            0% { transform: translateY(0); }
            50% { transform: translateY(-50px); }
            100% { transform: translateY(0); }
        }

        .message {
            font-size: 2em;
            color: darkblue;
        }

        .message span {
            display: inline-block;
            animation: bounce 1.5s ease-in-out infinite;
        }

        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-20px); }
        }
    </style>
</head>
<body>

<div class="container">
    <div class="balloons">
        <div class="balloon" style="background-color: red;"></div>
        <div class="balloon" style="background-color: yellow;"></div>
        <div class="balloon" style="background-color: blue;"></div>
        <div class="balloon" style="background-color: green;"></div>
    </div>
    <div class="message">
        🎉 Happy Birthday, <span>Andreas Sihombing!</span> 🎉
    </div>
</div>

</body>
</html>
