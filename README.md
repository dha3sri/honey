<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: linear-gradient(45deg, #ff9a9e, #fad0c4);
            font-family: Arial, sans-serif;
            margin: 0;
            text-align: center;
        }
        .container {
            animation: fadeIn 2s ease-in-out;
        }
        h1 {
            font-size: 60px;
            color: #fff;
            text-shadow: 3px 3px 10px rgba(0, 0, 0, 0.3);
            animation: bounce 2s infinite;
        }
        @keyframes bounce {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-20px);
            }
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Happy Birthday Nanna!🩷🎉🎂</h1>
    </div>
</body>
</html>
