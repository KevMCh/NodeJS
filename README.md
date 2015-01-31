---

#_Node.js_

---

[Node.js]:(http://nodejs.org/)

**¿Qué es [Node.js]?**

[Node]:(https://www.ibm.com/developerworks/ssa/opensource/library/os-nodejs/)

[Node] es un intérprete Javascript del lado del servidor cuya meta es permitir a un programador construir aplicaciones altamente escalables y escribir código que maneje decenas de miles de conexiones simultáneas en una sola una máquina física.

---

**Instalación de [Node.js] en Linux**

Lo primero que tenemos que realizar es ir a la página oficial de [Node.js] y descargar el repositorio git de [Node], para esto clicamos en el botón que pone "*Install*" y se iniciará la descarga.

Descomprimimos el archivo descargado,lo podemos hacer manualmente o mediante el siguiente comando:

                    $ tar -zxf node-v0.6.5.tar.gz
       
A continuación, entramos en la carpeta descomprimida del repositorio y ejecutamos el archivo Makefile, en dicho archivo están definidas las tareas necesarias para compilar el repositorio:

                    $ make
       
      >En el caso de que no tengamos el make instalado tendriamos que ejecutar el comando:
       
                    $ apt-get install make
       
Instalamos la aplicación en el sistema:

                    $ sudo make install
       
Mediante el siguiente comando podemos determinar que ya tenemos el [Node] instalado en nuestro sistema, ya que nos devuelve la versión instalada:

                    $ node -v

---

**Ejemplos de uso**

* "*Hola Mundo*" por funciones:

Creamos el fichero _HolaMundo.js_ con el siguiente contenido:

      function decir(palabra) {
        
         console.log(palabra);   
      }
      
      decir("Hola Mundo");
      
Ejecutando el comando con el [Node] nos dará el resultado esperado, imprimirá "_Hola Mundo_" por pantalla.

    $ node HolaMundo.js
      
* Consola [Node]:

Podemos abrir la consola Node, en donde escribir  instrucciones Javascript:

En el terminal introducimos:
    
    $ node

    > console.log("Hola Mundo");
    
He imprimirá "Hola Mundo".
    
Operadores matemáticos:
    
    > 34534+1212
    35746
    > 12*3
    36
    
    
  >Para cerrar la consola Node tenemos que pulsar dos veces "_Control + C_"

---

**Bibliografía**

* Página oficial de [Node.js]: 

_http://nodejs.org/_
      
* Páginas de información: 

_https://www.ibm.com/developerworks/ssa/opensource/library/os-nodejs/_

_http://es.wikipedia.org/wiki/Node.js_
      
* Tutoriales:

Libro para principiantes en Node.js por  Manuel Kiessling & Herman a.Junge:

_http://www.nodebeginner.org/index-es.html_
 
Página oficial Nodeschool:
 
_http://nodeschool.io/_