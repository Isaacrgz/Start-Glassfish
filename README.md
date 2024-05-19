# Instalar el Servidor Glassfish
1. Mueve el archivo **ZIP** en la ruta de interés.
> Ruta de ejemplo: C:/My-PC/documents/ServerGF
2. Descomprime el archivo **ZIP**.
> [!IMPORTANT]
> Es necesario haber instalado Java Development Kit (JDK), previamente.
# Iniciar el Servidor manualmente
1. Ubicate en a la carpeta **bin** principal.
> Ruta de ejemplo: C:/My-PC/documents/ServerGF/glassfish7/bin
2. Ejecuta el archivo ***asadmin.bat***.

3. Ejecuta el siguiente comando para *iniciar* el servidor.
```
   start-domain
```
   + Resultado esperado:
     ```
        Command start-domain executed successfully
     ```
# Apagar el Servidor GlassFish 
1. Ubicate en la carpeta **bin** principal.
> Ruta de ejemplo: C:/My-PC/documents/ServerGF/glassfish7/bin
2. Ejecuta el archivo ***asadmin.bat***.

3. Ejecuta el siguiente comando para *apagar* el servidor.
```
   stop-domain
```
   + Resultado esperado:
     ```
        Command stop-domain executed successfully
     ```
> [!NOTE]
> Para comprobar si el servidor esta iniciado o pagago, puedes dirigirte a la intefaz de administración (admin GUI).
> ```
>    http://localhost:4848
> ```
