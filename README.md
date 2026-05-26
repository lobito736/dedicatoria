<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Feliz Día Mamá</title>

<style>

body{
    margin:0;
    padding:20px;
    background:linear-gradient(135deg,#ffc0cb,#ffe6ee);
    font-family:Arial, sans-serif;
    display:flex;
    justify-content:center;
}

.card{
    width:100%;
    max-width:360px;
    background:white;
    border-radius:25px;
    padding:20px;
    text-align:center;
    box-shadow:0 10px 25px rgba(0,0,0,0.2);
}

/* FOTO */
.foto{
    width:100%;
    height:250px;
    object-fit:cover;
    object-position: center 0%;
    border-radius:20px;
    border:4px solid #ffd1dc;
}

/* TITULO */
h1{
    color:#ff4081;
    margin-top:15px;
}

/* FRASE */
p{
    color:#444;
    font-size:17px;
    line-height:1.6;
}

/* QR */
.qr-box{
    margin-top:20px;
    background:#fff0f5;
    border-radius:20px;
    padding:15px;
}

.qr-box img{
    width:150px;
    border-radius:15px;
}

.texto-qr{
    margin-top:10px;
    color:#ff4081;
    font-weight:bold;
    font-size:18px;
}

/* AUDIO */
audio{
    width:100%;
    margin-top:20px;
}

</style>
</head>

<body>

<div class="card">

    <!-- FOTO -->
    <img src="imagenes/audios/estefany.jpeg" class="foto">

    <!-- TITULO -->
    <h1>💖 Feliz Día de la Madre 💖</h1>

    <!-- FRASE -->
    <p>
        Gracias por todo tu amor,<br>
        cariño y apoyo 🌸<br><br>

        Eres la mejor mamá<br>
        del mundo 💕
    </p>

    <!-- QR -->
    

    <!-- AUDIO -->
    <audio controls autoplay loop controlsList="nodownload noplaybackrate">
        <source src="imagenes/audios/estefany.ogg" type="audio/ogg">
        Tu navegador no soporta audio.
    </audio>

</div>

</body>
</html>
