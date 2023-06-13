# Tarea3ArqEmergentes

Instrucciones iniciar el servicio:

1) Ubicarse en el directorio del proyecto
2) Una vez dentro, ejecutar los comandos necesarios para instalar los elementos a utilizar (node, express, sqlite3):
   - sudo apt install node npm sqlite3
   - npm init -y
   - npm install express sqlite3
3) Ahora es necesario configurar la base de datos, para ello se utilizan los siguientes comandos:
   - sqlite3
   - .open database.db
   - .save database.db
   - .databases
Verificar con este ultimo comando, si se retorna que main es "database.db"
4) Ya con todo lo necesario instalado, se pone en marcha el servicio con el comando: 
   - node index.js
5) Para realizar las consultas, se recomienda utilizar Postman
