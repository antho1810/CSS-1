# Que es CSS?
- Cascading Style sheets
- Describe la presentacion de docs HTML
- Un doc HTML puede tener multiples CSS

* Visitar "bootswatch.com"

# Como funciona?
- Selectores
- Seleccionar +1 elementos
- Propiedades

## Formas de importar CSS
- #1 -> Mas mala forma - No utilizar
```
<!DOCTYPE html>
<head>
    <title>Document</title>
</head>
<body style="color: tomato;">
    Anthony Feliz
</body>
</html>
```
- #2 -> Mas o menos mala forma - se podria utilizar
```
<!DOCTYPE html>
<head>
    <title>Document</title>
    <style>
        body{
            color: tomato;
        }
    </style>
</head>
<body>
Anthony Feliz
</body>
</html>
```
- #3 -> mejor forma - por archivos separados
```
<!DOCTYPE html>
<head>
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    Anthony Feliz
</body>
</html>
```
```
body{
    color: tomato;
}
```
