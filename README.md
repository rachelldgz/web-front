#Iniciar proyecto de git 
git init 
#Preparar archivos que se conviertan en commit 
git add .  
###< El punto es para agregar todos los archivos modificados>
#Crear commit con su mensaje
git commit -m "Aquí se escribe el mensaje"
#Agregar remoto "Solo la primera vez"
git remote add origin https://github.com/rachelldgz/web-front.git
#Enviar commits al servidor de GitHub
git push -u origint master
git push