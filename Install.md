#### Para poder instalar y configurar Github, hemos tenido que crearnos una cuenta primero en el GitHub virtual y crear un repositorio para así poder enlazarlo después.


## Instalación
* Tenemos que actualizar primero el equipo para poder instalarlo luego con el comando:


        sudo apt update


* Una vez actualizado el equipo tenemos que instalar git con el siguiente comando:


        sudo apt install git


## Configuración
* Una vez instalado ya git, configuramos y enlazamos el git virtual con el git instalado con los siguientes comandos de las credenciales:


        git config --global user.name "jmtatop01"
        git config --global user.email "jmtatop01@informatica.iesvalledeljerteplasencia.es"


* Para terminar de enlazarlos necesitamos crear una **clave SSH** con el comando:


        ssh-keygen -t rsa -b 4096 -C "jmtatop01@informatica.iesvalledeljerteplasencia.es"
