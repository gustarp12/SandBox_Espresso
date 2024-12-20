Repositorio creado como prueba, en base a un tutorial explicativo donde representan las funcionalidades de Kotlin dentro de Android Studio.
El mismo posee una estructura sencilla de prueba y entendible para poder ser legible y entendida al usuario.

Para la obtención de la carpeta de prueba es el siguiente directorio:
  app
    src
      androidTest
        Java
          com.example.android.testing.espresso.BasicSamble
Dentro de esta carpeta se encontrarán las pruebas realizadas, las mismas son simples y fueron desarrolladas en Kotlin. Las pruebas fueron las siguientes:
  1. Cambio de un Texto dentro de la misma pantalla (changeText_sameActivity).
       Paso 1: Se abre la aplicación
       Paso 2: Se ingresa el texto deseado
       Paso 3: Se hace tap al botón de "Change Text"
       Paso 4: Se hace una verificación de que el texto princial llamado "Hello Espresso!" cambiara por el texto ingresado en el paso 2
  2. Cambio de un Texto dentro de una pantalla nueva(changeText_newActivity).
       Paso 1: Se abre la aplicación
       Paso 2: Se ingresa el texto deseado
       Paso 3: Se hace tap al botón de "Change Text"
       Paso 4: Se hace una verificación de que el texto princial llamado "Hello Espresso!" cambiara por el texto ingresado en el paso 2
