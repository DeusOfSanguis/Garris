<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loading Screen</title>
    <style>
        body {
            margin: 0;
            height: 100vh;
            width: 100vw;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: #000;
        }
        img {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover;
            z-index: -1;
        }
        h1 {
            color: white;
            font-size: 3em;
            z-index: 1;
        }
    </style>
</head>
<body>
    <img src="https://raw.githubusercontent.com/DeusOfSanguis/Garris/main/lobotomia.png" alt="Loading Image">
    <h1>Loading, please wait...</h1>
</body>
</html>
