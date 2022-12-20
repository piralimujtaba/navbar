
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>animation</title>
    <style>
        * {
            margin: 0px;
            padding: 0px;
        }

        body {
            background-image: url(-13-wave.gif);
            background-repeat: no-repeat;
            background-size: cover;
        }

        .top {
            display: flex;
            justify-content: space-between;
            background: rgb(2, 0, 36);
            background: linear-gradient(90deg, rgb(55, 50, 139) 0%, rgba(9, 121, 112, 1) 35%, rgba(0, 212, 255, 1) 50%, rgba(0, 255, 166, 1) 78%);
        }

        .box1,
        .b2 {
            width: 60px;
            border-radius: 20px;
            height: 30px;
            text-align: center;
            font-size: x-large;
            color: rgb(0, 0, 0);
            font-weight: bold;
        }

        .box1 {
            border: 2px solid rgb(0, 0, 0);
            padding: 25px;
            background: rgb(2, 0, 36);
            background: linear-gradient(90deg, rgb(233, 94, 94) 0%, rgb(137, 192, 96) 21%, rgb(102, 100, 196) 50%, rgb(0, 255, 229) 78%);
        }

        .logo {
            border: 2px solid rgb(0, 0, 0);
            border-radius: 20px;
            overflow: hidden;
            justify-self: center;
        }

        .logo img {
            margin-bottom: -4px;
        }

        .b2 {
            padding: 25px;
            border: 2px solid rgb(87, 118, 201);
            background: rgb(2, 0, 36);
            background: linear-gradient(90deg, rgb(255, 152, 133) 0%, rgb(230, 90, 90) 35%, rgb(212, 68, 68) 50%, rgb(189, 33, 25) 78%);
        }

        .box1 {
            animation-name: left;
            animation-direction: normal;
            animation-duration: 8s;
            animation-iteration-count: infinite;
        }


        @keyframes left {
            0% {
                position: relative;
                top: 0px;
                left: 0px;
                background: rgb(2, 0, 36);
                background: linear-gradient(90deg, rgb(181, 65, 65) 0%, rgb(109, 161, 68) 21%, rgb(68, 66, 151) 50%, rgb(16, 147, 134) 78%);
            }

            12.5% {
                position: relative;
                top: 0px;
                left: 114px;
                padding-left: 25px;
                padding-top: 25px;
                padding-bottom: 25px;
                padding-right: 25px;
                background: rgb(2, 0, 36);
                background: linear-gradient(90deg, rgb(233, 94, 94) 0%, rgb(137, 192, 96) 21%, rgb(102, 100, 196) 50%, rgb(0, 255, 229) 78%);
            }

            25% {
                position: relative;
                top: 0px;
                left: 228px;
                padding-left: 30px;
                padding-top: 25px;
                padding-bottom: 25px;
                padding-right: 20px;
                /* transform: rotate(90deg); */
                background: rgb(2, 0, 36);
                background: linear-gradient(90deg, rgb(181, 65, 65) 0%, rgb(109, 161, 68) 21%, rgb(68, 66, 151) 50%, rgb(16, 147, 134) 78%);
            }

            37.5% {
                position: relative;
                top: 0px;
                left: 342px;
                padding-left: 35px;
                padding-top: 25px;
                padding-bottom: 25px;
                padding-right: 15px;
                background: rgb(2, 0, 36);
                background: linear-gradient(90deg, rgb(233, 94, 94) 0%, rgb(137, 192, 96) 21%, rgb(102, 100, 196) 50%, rgb(0, 255, 229) 78%);
            }

            50% {
                position: relative;
                top: 0px;
                left: 456px;
                padding-left: 40px;
                padding-top: 25px;
                padding-bottom: 25px;
                padding-right: 10px;
                background: rgb(2, 0, 36);
                background: linear-gradient(90deg, rgb(181, 65, 65) 0%, rgb(109, 161, 68) 21%, rgb(68, 66, 151) 50%, rgb(16, 147, 134) 78%);
            }

            62.5% {
                position: relative;
                top: 0px;
                left: 570px;
                padding-left: 45px;
                padding-top: 25px;
                padding-bottom: 25px;
                padding-right: 5px;
                background: rgb(2, 0, 36);
                background: linear-gradient(90deg, rgb(233, 94, 94) 0%, rgb(137, 192, 96) 21%, rgb(102, 100, 196) 50%, rgb(0, 255, 229) 78%);
            }

            75% {
                position: relative;
                top: 0px;
                left: 400px;
                padding-left: 40px;
                padding-top: 25px;
                padding-bottom: 25px;
                padding-right: 10px;
                background: rgb(2, 0, 36);
                background: linear-gradient(90deg, rgb(181, 65, 65) 0%, rgb(109, 161, 68) 21%, rgb(68, 66, 151) 50%, rgb(16, 147, 134) 78%);
            }

            87.5% {
                position: relative;
                top: 0px;
                left: 200px;
                padding-left: 35px;
                padding-top: 25px;
                padding-bottom: 25px;
                padding-right: 15px;
                background: rgb(2, 0, 36);
                background: linear-gradient(90deg, rgb(233, 94, 94) 0%, rgb(137, 192, 96) 21%, rgb(102, 100, 196) 50%, rgb(0, 255, 229) 78%);
            }

            100% {
                position: relative;
                top: 0px;
                left: 0px;
                padding-left: 25px;
                padding-top: 25px;
                padding-bottom: 25px;
                padding-right: 25px;
                background: rgb(2, 0, 36);
                background: linear-gradient(90deg, rgb(181, 65, 65) 0%, rgb(109, 161, 68) 21%, rgb(68, 66, 151) 50%, rgb(16, 147, 134) 78%);
            }


        }

        .b2 {
            animation-name: right;
            animation-direction: normal;
            animation-duration: 8s;
            animation-iteration-count: infinite;
        }

        @keyframes right {
            0% {
                position: relative;
                top: 0px;
                left: 0px;
                background: rgb(2, 0, 36);
                background: linear-gradient(90deg, rgb(185, 93, 76) 0%, rgb(177, 59, 59)35%, rgb(80, 149, 50) 50%, rgb(52, 93, 159) 78%);
            }

            12.5% {
                position: relative;
                top: 0px;
                left: -114px;
                padding-right: 30px;
                padding-top: 25px;
                padding-bottom: 25px;
                padding-left: 20px;
                background: rgb(2, 0, 36);
                background: linear-gradient(90deg, rgb(243, 84, 57) 0%, rgb(240, 65, 65) 35%, rgb(179, 250, 66) 50%, rgb(60, 105, 253)78%);
            }

            25% {
                position: relative;
                top: 0px;
                left: -228px;
                padding-right: 35px;
                padding-top: 25px;
                padding-bottom: 25px;
                padding-left: 15px;
                background: rgb(2, 0, 36);
                background: linear-gradient(90deg, rgb(185, 96, 80) 0%, rgb(165, 63, 63) 35%, rgb(95, 170, 54) 50%, rgb(33, 69, 159) 78%);

            }

            37.5% {
                position: relative;
                top: 0px;
                left: -342px;
                padding-right: 40px;
                padding-top: 25px;
                padding-bottom: 25px;
                padding-left: 10px;
                background: rgb(2, 0, 36);
                background: linear-gradient(90deg, rgb(255, 101, 74) 0%, rgb(255, 63, 63)35%, rgb(115, 255, 76) 50%, rgb(66, 98, 255) 78%);

            }

            50% {
                position: relative;
                top: 0px;
                left: -456px;
                padding-right: 45px;
                padding-top: 25px;
                padding-bottom: 25px;
                padding-left: 5px;
                background: rgb(2, 0, 36);
                background: linear-gradient(90deg, rgb(189, 96, 80) 0%, rgb(197, 78, 78) 35%, rgb(76, 169, 58) 50%, rgb(22, 48, 141) 78%);

            }

            62.5% {
                position: relative;
                top: 0px;
                left: -570px;
                padding-right: 45px;
                padding-top: 25px;
                padding-bottom: 25px;
                padding-left: 5px;
                background: rgb(2, 0, 36);
                background: linear-gradient(90deg, rgb(255, 86, 70) 0%, rgb(255, 95, 95) 35%, rgb(74, 255, 57) 50%, rgb(41, 66, 255) 78%);

            }

            75% {
                position: relative;
                top: 0px;
                left: -400px;
                padding-right: 40px;
                padding-top: 25px;
                padding-bottom: 25px;
                padding-left: 10px;
                background: rgb(2, 0, 36);
                background: linear-gradient(90deg, rgb(188, 99, 83) 0%, rgb(173, 65, 65) 35%, rgb(75, 159, 55) 50%, rgb(20, 29, 149) 78%);

            }

            87.5% {
                position: relative;
                top: 0px;
                left: -200px;
                padding-right: 35px;
                padding-top: 25px;
                padding-bottom: 25px;
                padding-left: 15px;
                background: rgb(2, 0, 36);
                background: linear-gradient(90deg, rgb(255, 105, 79) 0%, rgb(255, 94, 94) 35%, rgb(80, 255, 68) 50%, rgb(36, 91, 255) 78%);

            }

            100% {
                position: relative;
                top: 0px;
                left: -0px;
                padding-right: 45px;
                padding-top: 25px;
                padding-bottom: 25px;
                padding-left: 25px;
                background: rgb(2, 0, 36);
                background: linear-gradient(90deg, rgb(189, 100, 84) 0%, rgb(172, 59, 59) 35%, rgb(49, 164, 62) 50%, rgb(22, 49, 156) 78%);

            }
        }

        .logo {
            animation-name: display;
            animation-duration: 8s;
            animation-direction: normal;
            animation-iteration-count: infinite;

        }


        @keyframes display {
            0% {
                position: relative;
                top: 0px;


            }

            12.5% {
                position: relative;
                top: 0px;

            }

            25% {
                position: relative;
                top: 0px;
            }

            37.5% {
                position: relative;
                top: 0px;

            }

            50% {
                position: relative;
                top: 0px;


            }

            56.25% {
                position: relative;
                top: -200px;

            }

            62.5% {
                position: relative;
                top: -200px;
            }

            68.75% {
                position: relative;

                top: 0px;

            }

            75% {
                position: relative;
                top: 0px;

            }

            87.5% {
                position: relative;
                top: 0px;

            }

            100% {
                position: relative;
                top: 0px;

            }


        }
    </style>
</head>
<nav class="top">
    <div class="box1">Aly,s</div>
    <div class="logo">
        <img src="-11-piano.gif" alt="" width="100px" height="81px">
    </div>
    <div class="b2">Music</div>
</nav>

</body>

</html>
