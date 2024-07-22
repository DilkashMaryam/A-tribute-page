<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Document</title>
</head>
<body>
    <div>
        <h1>Hello</h1>
    </div>
</body>
</html>
div{
    height: 300px;
    width: 100%;
    background-color: black;
    display: flex;
    justify-content: center;
    animation-name: fordiv;
    animation-duration: 3s;
    animation-iteration-count: 3;
}
@keyframes fordiv {
    from{
        width: 10%;
        background-color: aqua;
    }
    to{
        width: 100%;
        background-color: blue;
    }
}
h1{
    color: white;
}
