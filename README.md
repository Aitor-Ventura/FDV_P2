## 🎈 Uploading files to Perforce

*The Unity project was not uploaded to this repository due to its size.

The process followed the following points:
1. Get access to the ULL's VPN following their [guide](https://docs.google.com/document/d/1xhSRVqo6y5HYtQQtBemLEwDG6a_yjGlzrxjwuYxIQAk/edit).
2. Download Perforce and its tool called [P4V](https://www.perforce.com/products/helix-core).
3. Log in to the University's remote Perforce server with your institutional account and with the charset Windows-1252.
4. Create a new *workspace* that will only track the *FDV2233* depo. Choose a name for your local depo and set the directory to initialize the cloning process. 

![Imagen de paso 4](Paso4.1.png)

5.Select the depo you want to be cloned and click on the button that says "Get Latest". 

![Get latest](Paso5.1.png)

6. Within the *workspace*, create a folder that will contain the different exercises.
7. On the menu above, click on *Refresh*, select the parent folder you created in the previous point, and select the option *Reconcile offline work*. In the menu that appears, select *Reconcile* down below.

![Reconcile](Paso7.1.png)

8. With all the changes uploaded (the equivalent to *commit* in Git), go to the *Pending* tab, select your changes, and click "Submit" (the equivalent to *push*).

![Push](Paso8.1.png)

Congrats! All done 🤩. 

## 🎈 Subir archivos a Perforce

*El proyecto de Unity no ha sido subido al repositorio debido a su tamaño.

El proceso siguió los siguientes puntos:
1. Acceder a la VPN de la Universidad de La Laguna siguiendo su [guía](https://docs.google.com/document/d/1xhSRVqo6y5HYtQQtBemLEwDG6a_yjGlzrxjwuYxIQAk/edit).
2. Descargar Perforce y su herramienta [P4V](https://www.perforce.com/products/helix-core).
3. Iniciar sesión en el servidor remoto de Perforce de la Universidad con la cuenta institucional y con el set de caracteres Windows-1252.
4. Crear un nuevo *workspace* que sólamente siguiera el repositorio *FDV2233* con el nombre deseado y el directorio donde se quiere inicializar la clonación.

![Imagen de paso 4](Paso4.1.png)

5. Seleccionar el repositorio que se quiere clonar y darle al botón "Get Latest", consiguiendo una clonación completa.

![Get latest](Paso5.1.png)

6. En el *workspace*, crear la carpeta específica del alumno que contendrá las diferentes prácticas.
7. Clicar en el menú de arriba a *Refresh*, seleccionar la carpeta padre anterior, elegir la opción *Reconcile offline work*, y luego seleccionar *Reconcile*.

![Reconcile](Paso7.1.png)

8. Con todos los cambios subidos (equivalente a *commit* en Git), ir a la pestaña *Pending*, seleccionar los cambios, y darle a "Submit" (equivalente a *push*).

![Push](Paso8.1.png)

¡Felicidades! Todo hecho 🤩.
