<!DOCTYPE html>
<html lang="en">

<head>
    <script src="https://kit.fontawesome.com/125dfb632e.js" crossorigin="anonymous"></script>

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">

    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ReadMe</title>

    <style>
        .container {
            background-color: white;
            height: max-content;
            display: flex;
            border-bottom: 20px solid #FFCC00;
            border-radius: 12px;
            box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
            font-family: 'Roboto', sans-serif;
        }

        .container img {
            width: 270px;
        }

        .container .inner_left {
            width: 70%;
            text-align: center;
            display: flex;
            flex-direction: column;
            justify-content: center;
            position: relative;
        }

        .container .inner_right {
            width: 30%;
            border-left: 2px solid black;
            border-radius: 10px;
            padding-left: 15px;
        }

        .container .social {
            display: flex;
            flex-direction: column;
            width: max-content;
            position: absolute;
            /* top: 0; */
            left: 5px;
        }

        .container .social i{
            font-size: 24px;
            margin: 4px;
            border-radius: 100%;
            border: 1px solid black;
            display: inline;
            padding: 7px;
            color: #FFCC00;
            background-color: black;
        }

        h1,h2,h6 {
            margin: 8px;
        }
    </style>
</head>

<body>
    <div class="container">
        <div class="inner_left">
            <h1>WELCOME !</h1>
            <h2>It's me AenR</h2>
            <h6>Computer programming :computer:</h6>
            <div class="social">
                <i class="fa-brands fa-linkedin-in"></i>
                <i class="fa-solid fa-envelope"></i>
            </div>
        </div>
        <div class="inner_right">
            <img src="./logo.png" alt="logo">
        </div>
    </div>
</body>

</html>
