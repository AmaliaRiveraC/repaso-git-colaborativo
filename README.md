# repaso-git-colaborativo

#Dueño/administrador del repositorio:
#crear el repositorio desde interfaz de github
#Clona el repositorio en su equipo
#Entra desde la consola a su carpeta
#Crea un archivo index vacío

#Colaborador:
#Forkea el repositorio donde colaborara
#Clona su repositorio en su equipo

#Dueño/administrador del repositorio:
#Da un git stage para deshacer lo que ha subido a master
#git branch html-init (crea la nueva rama donde estaremos trabajando una nueva funcionalidad)
#modifica el archivo index (agrega contenido)
#git add .
#git commit -m "agregando contenido"
#git push origin html-init (añado el contenido a la nueva rama donde estaré trabajando)
#después de pushear vamos a nuestra interfaz de github para hacernos un pull request, hacer el merge y borrar la rama de manera remota.
#Para borrar nuestra rama de manera local desde consola nos cambiamos a nuestra rama master
#git checkout master
#git branch -D html-init (borra la rama de manera local)

#Colaborador:
#git remote -v (para ver de donde está jalando información y mandando)
#Si no aparece el repositorio al que le dimos fork y solo parece nuestra propia dirección en fetch y en push
#git remote add upstream http://(url)
#git remote -v (volvemos a revisar cuál es nuestro upstream, de donde jalamos y a donde mandamos nuestra información)
#Para actualizar nuestro repositorio remoto:
#git fetch upstream
#git merge upstream/master (para mezclar lo que descargamos del upstream a nuestro master local)
#git branch agregar-perrito (crea el colaborador una nueva rama donde trabajar estos cambios)
#git checkout agegar-perrito (se mueve a la rama donde trabajara los cambios) 
#agregamos información a los archivos y subimos a nuestro reporitorio remoto
#git add .
#git commit -m "agregar imagen de perrito"
#git push origin agregar-perrito
#desde la interfaz de github hacemos el pull request al repositorio(upstream)

#Dueño/administrador del repositorio original
#revisa el pull request/ lo acepta / y hace el merge de manera remota
#para ver las actualizaciones de manera local
#git pull origin master
#ya están todos los repositorios sincronizados


