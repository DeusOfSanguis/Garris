<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loading Screen</title>
    <style>
        body {
            margin: 0;
            overflow: hidden;
            background-color: #000;
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }
        img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        h1 {
            position: absolute;
            top: 20px;
            left: 50%;
            transform: translateX(-50%);
            color: white;
            font-size: 2em;
            text-shadow: 2px 2px 5px black;
        }
    </style>
</head>
<body>
    <h1>Loading, please wait...</h1>
    <img src="https://raw.githubusercontent.com/DeusOfSanguis/Garris/main/lobotomia.png" alt="Loading Image">
</body>
</html>
