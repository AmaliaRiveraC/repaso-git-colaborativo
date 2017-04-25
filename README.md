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
#después de pushear vamos a nuestra interfaz de github para hacernos un pull request

#Colaborador:
#git remote -v (para ver de donde está jalando información y mandando)
#Si no aparece el repositorio al que le dimos fork y solo parece nuestra propia dirección en fetch y en push
#git remote add upstream http://(url)
#git remote -v (volvemos a revisar cuál es nuestro upstream, de donde jalamos y a donde mandamos nuestra información)
