# Tutorial - Template 1
> Presentación con Bemaer | Personalización sobre el tema: AnnArbor

<figure display="inline">
  <span>
    <img width="45%" src="https://res.cloudinary.com/dvnjjcrs1/image/upload/v1603554246/img/car%C3%A1tula-Ann_ilihhw.png" alt="carátula de la presentación"></span>
  <span>
    <img width="45%" src="https://res.cloudinary.com/dvnjjcrs1/image/upload/v1603554384/img/Contents_a47q3y.png" alt="contenido de la presentación">
  </span>
</figure>

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

Por otro lado, el uso del paquete `graphicx` es necesario ya que se incluirán imágenes como el logotipo de la institución y de la facultad.

<object data="https://www.cisco.com/c/es_mx/support/docs/unified-communications/unified-attendant-console-enterprise-edition/200175-Cisco-Unified-Attendant-Console-Licensin.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="https://www.cisco.com/c/es_mx/support/docs/unified-communications/unified-attendant-console-enterprise-edition/200175-Cisco-Unified-Attendant-Console-Licensin.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="https://www.cisco.com/c/es_mx/support/docs/unified-communications/unified-attendant-console-enterprise-edition/200175-Cisco-Unified-Attendant-Console-Licensin.pdf">Download PDF</a>.</p>
    </embed>
</object>
