---
title: 'Guía Completa: Cómo Instalar Node.js en Windows y Linux (Paso a Paso)'
description: 'Guía completa de cómo instalar Node.js en Windows y Linux'
pubDate: '29 Sep 25'
heroImage: '../../assets/guia-de-instalacion-node-js.webp'
tags: ["node.js", "guia", javascript]

---

En un artículo anterior vimos algunas de las ventajas de usar y aprender a usar **Node.js**; pero ahora, ¿cómo podemos empezar nuestro camino en este entorno? Pues el primer paso es la **instalación de Node.js**. En esta guía completa te mostraremos los métodos más sencillos para que puedas tener **Node.js** funcionando tanto en **Windows** como en **Linux**.

### Instalación de Node.js en Windows

Existen varias formas de **instalar Node.js en Windows**, la más sencilla es descargando el instalador oficial desde la página de Node.js. Este es el método más recomendado para principiantes, ya que es rápido y directo.

![captura de pantalla](/article-images/step-0-node-js.png)

Una vez descargado el instalador, ábrelo, acepta la advertencia que te emerge y presiona **Next**. Luego marca la casilla para aceptar los términos y condiciones y presiona **Next**. La ventana actual te ofrece la oportunidad de cambiar la carpeta de destino de Node.js. Si estás de acuerdo con ella, solo da clic en **Next**.

![captura de pantalla](/article-images/step-1-node-js.png)

![captura de pantalla](/article-images/step-2-node-js.png)

![captura de pantalla](/article-images/step-3-node-js.png)

**Herramientas para módulos nativos:** En esta ventana, generalmente no se marca la casilla para instalar herramientas como **Chocolatey**. Si lo haces, se abrirá una ventana de PowerShell que comenzará la instalación de este programa al terminar la instalación regular de Node.js.

![captura de pantalla](/article-images/step-4-node-js.png)

![captura de pantalla](/article-images/step-5-node-js.png)

![captura de pantalla](/article-images/step-7-node-js.png)

Finalmente, pasa a la última casilla en la que debes dar clic a **Install**. Al terminar, podrás verificar si la instalación fue exitosa.

![captura de pantalla](/article-images/step-6-node-js.png)

---

### Instalación de Node.js en Linux

La **instalación de Node.js en Linux** es muchas veces más intuitiva si ya te has familiarizado con la línea de comandos. A continuación, te mostramos dos métodos efectivos para usuarios de distribuciones como **Ubuntu** y **Debian**.

#### Método 1: Usando el paquete .deb

Este método es útil si prefieres la instalación manual. Primero, descarga el paquete `.deb` de la página oficial. Una vez que lo tengas, abre la terminal de Ubuntu y avanza a la carpeta de descargas con el comando: `cd Descargas`

Posteriormente, ejecuta el siguiente comando:

``` bash
sudo dpkg install <nombre_del_archivo_.deb>

```

<br/>

Acepta los términos de instalación y comprueba el éxito con el comando: `node -v`

#### Método 2: La manera más recomendada usando NVM

La segunda manera, y la **más recomendada para desarrolladores**, es usar **NVM (Node Version Manager)**. NVM te permite tener múltiples versiones de Node.js instaladas simultáneamente, lo cual es extremadamente útil para trabajar en diferentes proyectos.

Para instalarlo, abre la terminal y ejecuta el siguiente comando:

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash
```

Luego, reinicia la shell con este comando: `\. "$HOME/.nvm/nvm.sh`

Por último, puedes instalar la versión LTS (Long Term Support) de Node.js con el comando:

```bash
nvm install --lts
```

Puedes verificar la correcta instalación con el clásico comando: `node -v`.

---

### Verificación de la Instalación y Próximos Pasos

Una vez que hayas completado la **instalación de Node.js**, es crucial que verifiques que todo esté funcionando correctamente.

Abre una nueva terminal (o PowerShell en Windows) y ejecuta el siguiente comando para verificar la versión de Node.js:

```bash
node -v
```

También puedes verificar la versión de **npm** (Node Package Manager), que se instala automáticamente con Node.js, con el siguiente comando:

```bash
npm -v
```

Si estos comandos te devuelven un número de versión, ¡felicidades! Has completado la **instalación de Node.js** exitosamente. Ahora estás listo para empezar a programar.

Espero que este tutorial te haya sido de gran utilidad para iniciar tu camino con Node.js. ¡Mucho éxito en tus proyectos! 🚀
