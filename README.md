# Informática II - UPE

En este repositorio se encuentra la clase teórica de la cursada referida a Sistemas de Seguimiento de Errores.

Las mismas están armadas con html, javascript y css, utilizando [reveal.js](https://github.com/hakimel/reveal.js/)


### Cómo ver las presentaciones localmente

Reveal utiliza [node](https://nodejs.org/) como plataforma, por lo tanto, deberá estár instalado.

Una vez cumplidas las dependencias, pueden clonar el repositorio

```bash
$ git clone git@github.com:rapofran/upe-infotmatica-II.git
```

Instalar los paquetes node que reveal necesita:

```bash
$ cd upe-infotmatica-II
$ npm install -f
```

y correr el servidor localmente:

```bash
$ grunt serve
```

Podrán acceder a las clases desde su navegador ingresando a dirección `http://localhost:8000`


## Descargar las clases en PDF

Reveal provee un mecanismo para generar una versión imprimible de las presentaciones.
Para esto pueden, o bien utilizar el link que es provee en la primer página de cada clase,
o :

* Agregar en la url un parámetro `print-pdf` por ejemplo: `http://localhost:8000/index.html?print-pdf`

Para descarga un pdf, pueden utilizar la opción de "imprimir a un archivo pdf" del navegador

* presionamos Ctrl+p (imprimir página)
* en la configuración de la impresora, seleccionamos la opción "imprimir a un archivo pfd"


### Colaboraciones

Pueden forkear el repositorio y modificar cualquiera de los archivos.
Son bienvenidos pull requests con correcciones u otros aportes constructivos.