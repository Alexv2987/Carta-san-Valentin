<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Subir Imagen</title>
</head>
<body>
    <h1>Subir Imagen del Día</h1>
    <form action="/upload" method="post" enctype="multipart/form-data">
        <label for="image">Selecciona una imagen:</label>
        <input type="file" id="image" name="image" accept="image/*" required>
        <br><br>
        <button type="submit">Subir y Enviar</button>
    </form>
</body>
</html>
