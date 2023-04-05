# EJEJRCICIO-6
TAREA DE BOOTCAMP
<!DOCTYPE html>
<html lang="en">
<head>
    
    <title>Selectores, pseudo-clases, y pseudoelemetos</title>
    <link rel="stylesheet" href="tarea6.css">
</head>
<body>
    <button class="btn">BOTON</button>
    
</body>
</html>


CSS:
.boton:hover {
    background-color : green;
    color: white;
}
.boton::before {
    content: "pase por encima"
}
.boton::after {
    content : "HECHO!"
}
