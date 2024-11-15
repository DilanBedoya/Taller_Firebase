
Nombres :

-Dilan Bedoya
-
-Alex Cardenas 
-
Autenticación y Subida de Archivos en Ionic con Firebase
Pasos
1. Crear Proyecto
Instala Ionic CLI y Node.js, luego crea el proyecto:

ionic start firebase-auth-upload blank --type=angular



2 .Configurar Firebase
Crea un proyecto en Firebase y activa la autenticación por correo. Configura la aplicación con las credenciales de Firebase en environment.ts.


![image](https://github.com/user-attachments/assets/ac2632a4-12fb-4ebc-a668-c1d097a593d5)(auntenticacion)

-

3 .Instalar Dependencias
npm install firebase @angular/fire

-

4 .Autenticación y Subida de Archivos
Implementa autenticación con AngularFireAuth y subida de archivos con AngularFireStorage.

5 . Probar y generar la apk
-
-Ejecuta la app:
-
-ionic serve
-
![image](https://github.com/user-attachments/assets/fefe4f5b-b0a3-473e-b5b0-9f466221889e) (aplicacion)
Genera la APK:
-
---ionic capacitor build android
-

-APK
![image](https://github.com/user-attachments/assets/0fcd16f8-3c26-4db4-9fa8-f0605b4f7f65)
-
-
![image](https://github.com/user-attachments/assets/97827330-5ae7-4b78-97e4-44d53fdaedd9)
-

Los aportes establecidos por cada uno de los estudiantes se realizaron a traves de comits ,por una parte esta Alex Cardenas que empezo el proyecto siguiendo la guia y creo el APK Y por otra parte Dilan Bedoya se encargo de configurar el database y configurar el path 

Recursos
https://devdactic.com/ionic-firebase-auth-upload
https://firebase.google.com/docs



