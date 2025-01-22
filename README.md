<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="IE=edge">
    <title>xRobinBlue || comunity</title>
</head>
<body>
    <script src="script.js"></script>
    <link rel="stylesheet" href="style.css">
    <header>
     <img src="xrobinblue.png"></img>
     <h1>xRobinBlue</h1>
    </header>
    <button id="button1" onclick="dev();">únete</button>
    <center>
        <p>este streamer/youtuber suele subir contenido de roblox y entre otras cosas<br>sigue a xrobinblue en todas sus redes sociales</p><br>
        <br><h4>nota:es muy divertido</h4>
    <button id="button2" onclick="dev();">únete</button>
    <h6>hecho por mtmeri x xrobinblue</h6>
    </center>
  <style>
    img{
    border-radius: 50%;
}
header{
    background-image: linear-gradient(40deg, blue, royalblue);
    margin: -6px;
    animation: delay 4s ease infinite;
}
@keyframes delay{
    0%{background-image: linear-gradient(40deg, blue, royalblue);}
    50%{background-image: linear-gradient(40deg, blue, royalblue, blue);}
    100%{background-image: linear-gradient(40deg, royalblue, blue);}
}
#button1{
    position: relative;
    left: 50px;
    background-color: blue;
    color: white;
    border-radius: 30px;
    border-color: royalblue;
    bottom: 100px;
}
#button2{
    background-color: blue;
    color: white;
    border-radius: 30px;
    border-color: royalblue;
    position: relative;
    top: 100px;
    width: 100px;
    height: 50px;
    font-size: 30px;
}
button:hover{
    background-color: royalblue;
    border-color: blue;
}
body{
    background-color: darkblue;
    color: white;
}
p{
    font-size: 30px;
}
h1{
    position: relative;
    left: 200px;
    bottom: 60px;
}
h6{
    position: relative;
    left: 600px;
}
  </style>
  <script>
    function dev(){
    alert('bienvenido a xRobinBlue')
}
  </script>
</body>
</html>
