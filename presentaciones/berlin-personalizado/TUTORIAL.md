# Tutorial - Berlin personalizado
<!-- Cambiar está línea por una imágen -->

## Preámbulo 📖
Para empezar nuestra presentación es importante indicar como primera línea de nuestro archivo *.tex* la clase de documento que vamos a trabajar, en este caso debido a que es una presentación usamos Beamer.
```
\documentclass{beamer}
```
<br />
Los paquetes necesarios para el template se muestran a continuación.

```
\usepackage[utf8]{inputenc}
\usepackage{graphicx}
```
El paquete `inputenc` con la opción de `utf8` permitirá el uso de caracteres especiales, sin esto veríamos por ejemplo `Politécnica` como `Politcnica` puesto que la `é` no se encuentra disponible en ASCII no extendido que es el que entiende por defecto LaTeX sin no se especifica este paquete con esta opción.

Cabe recalcar que LaTeX ha definido por defecto `\usepackage[utf8]{inputenc}` desde abril del 2018 por lo que especificar el uso del paquete `inputenc` es necesario para versiones previas.