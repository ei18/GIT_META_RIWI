#Configuracion

SSH => para conectar git a un servidor
HTTPS => para conectar git a un computador

Comando para conocer la version de github:

    git -v
    git --version

Comando para configurar git por primera vez:

    git config --global user.name "Keity"
    git config --global user.email "keityortegam@gmial.com"

Comando para ver que usuario esta configurado o con que correo electronico:

    git config --global user.name
    git config --global user.email 
    git config --list

Comando para inicializar git en un directorio:

    git init    

Comando para ver el estado de los archivos:

    git status

Comando para ver todas las versiones de mi proyecto:

    git log (trae toda la informacion)
    git log --oneline (Trae la informacion necesaria en una sola linea)

Comando para navegar entre versiones:

    git checkout (identificador de la version o nombre de la rama)

    git checkout -- . // Atajo

Pasos para crear una version de mi codigo

    1. Agregar los cambios => 
        git add .
        git add *.js
        git add *.html (Agregar solo un tipo de archivo ya sea css, js, html...)
        git add index.html(nombre del archivo para agregr uno en especifico)


    2. Comprometer los archivos

        git commit -m "Descripcion del commit"






