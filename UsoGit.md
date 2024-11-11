A continuación, agregar una lista de comandos básicos que tenemos que utilizar para documentar en **GitHub**.
* Empezaré con un comando para clonar el repositorio que está en virtual para descargarla en local en tu equipo:


        git clone https://github.com/tu_usuario/tu_repositorio-TuNombre.git


* Para poder iniciar un nuevo repositorio en local se utiliza el siguiente comando:


        git init


* Para configurar tu nombre de usuario  para todos los repositorios  locales en el equipo:


        git config --global user.name "Tu Nombre"


* Para configurar el correo electrónico asociado con Git en todos los repositorios:


        git config --global user.email "tu_correo@example.com"


* Muestra si la configuración dada en Git está correctamente:


        git config --list


* Muestra el estado de los archivos en el repositorio:


        git status


* Añade un archivo específico al área de preparación para ser confirmado:


        git add <nombre_archivo>


* Añade todos los archivos modificados al área de preparación:


        git add .


* Guarda los cambios en el repositorio local:


        git commit -m "mensaje del commit"


* Añade y guarda los cambios de todos los archivos que ya estaban en seguimiento:


        git commit -am "mensaje del commit"


* Sube los cambios de la rama **main** al repositorio remoto en **GitHub**:


        git push origin main


* Descarga los cambios del repositorio remoto y los aplica a tu rama local main:


        git pull origin main


* Crea una nueva rama llamada **<nombre_rama>**:


        git branch <nombre_rama>


* Cambia a la rama especificada (<nombre_rama>):


        git checkout <nombre_rama>


* Muestra el historial de commits realizados en la rama actual:


        git log


* Muestra los cambios no confirmados:


        git diff
