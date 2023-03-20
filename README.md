# Guia desde **cero** y en **español** para iniciar con un mod sencillo en minecraft usando **Forge** 1.19  y JDK 17 (2023)

## ***Parte #1***, preparando todo para programar

### Recomiendo tener un nivel intermedio programando y usando Java, es escencial para entender la syntaxis***En español***

---

#### Requisitos/software para empezar:
* Java 17
    * https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html
* IDE eclipse
    * https://www.eclipse.org/downloads/
* MDK forge 1.19 (No instalador forge)
    * https://files.minecraftforge.net/net/minecraftforge/forge/

---

#### Una ves instalado todo pasamos a crear la carpeta del mod

* Primero extraemos el contenido del mdk.zip que descargamos y seleccionamos solo algunos de los archivos:
    * La carpeta con nombre **gradle**
    * la carpeta con nombre **src**
    * build.gradle
    * gradle.propeties
    * gradlew
    * gradlew.bat
    * setting.gradle

la carpeta nos deberia quedar asi:

![Imagen de carpeta #1](/img/tree1.png)

Ya esta casi todo para empezar a programar. La carpeta llamada "com" incluye un mod de ejemplo, pero como en este caso no nos interesa vamos a borrar su contenido dejando la carpeta "com" vacia, para despues crear 2 nuevas carpetas **dentro de com**.

eliminamos la carpeta **example** y creamos un nuevo arbol de dos carpetas que quedaria de la siguiente manera:

* deliaaan (tu nombre o de tu organizacion)
    * miprimermod (nombre que llevara el mod)

![arbol de carpetas corregido](/img/anima2.gif)

***ES MUY IMPORTANTE QUE NO USES MAYUSCULAS EN EL NOMBRE DE ESTAS CARPETAS, SOLO MINUSCULAS***

---
Casi terminamos la primer parte, ahora toca abrir nuestro IDE intellij



