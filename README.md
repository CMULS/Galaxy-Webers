<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Frosted Glass Credit Card</title>
    <!-- Import the Inconsolata font from Google Fonts -->
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Inconsolata&display=swap">

    <style>
        /* Reset default margins and paddings */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background: url('https://images.pexels.com/photos/1655166/pexels-photo-1655166.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260') no-repeat center center;
            background-size: cover;
            display: grid;
            font-family: 'Inconsolata', monospace;
            min-height: 100vh;
            place-items: center;
        }

        /* Create the frosted blurry glass effect */
        .card {
            position: relative;
            width: 300px;
            height: 180px;
            border-radius: 15px;
            overflow: hidden;
            background: rgba(255, 255, 255, 0.3);
            backdrop-filter: blur(10px) saturate(100%) contrast(45%) brightness(130%);
            padding: 20px;
            text-align: center;
            color: #fff;
        }

        /* Style for the card text */
        .card_text {
            font-size: 16px;
            line-height: 1.5;
            font-weight: bold;
        }

        /* Style for the small text */
        .card_text small {
            font-size: 12px;
        }

        /* Style for the Visa logo */
        svg {
            width: 40px;
            margin-top: 10px;
        }
    p {
     color: #fff;
}
    </style>
</head>
<body>
    <div class="card">
        <div class="card_text">
            Chibesa D Mulenga
            <br>
            VISA
            <br>
            7426 3523 6143 1218
            <br>
            <small>11/26</small>
        </div>
        <!-- Insert Visa logo here -->
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 48 24">
            <!-- Replace the following path data with the actual Visa logo path data -->
            <path d="M4 0l4 24h8l-4-24h-8zm20 0l4 24h8l-4-24h-8z"/>
        </svg>
    </div>
</body>
<p> Above is a frosted glass credit card theme. </p>
</html>

