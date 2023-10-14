## Instala Kali Linux en VirtualBox en Windows // Paso a paso

### ADVERTENCIA: Los siguientes enlaces descargarán archivos automáticamente, ¡así que solo haga clic en ellos desde donde va a instalarlo!

1. Descargar VirtualBox:

   - Para Windows: (https://download.virtualbox.org/virtualbox/7.0.10/VirtualBox-7.0.10-158379-Win.exe)

2. Descargar el paquete de extensiones:

   - (https://download.virtualbox.org/virtualbox/7.0.10/Oracle_VM_VirtualBox_Extension_Pack-7.0.10.vbox-extpack)

3. Descargar Kali Linux:

   - (https://cdimage.kali.org/kali-2023.2/kali-linux-2023.2-virtualbox-amd64.7z)

4. Debes activar el Subsistema de Windows para Linux. Para hacerlo, escribe "Características de Windows" en la barra de búsqueda del menú de Windows, ábrelo, desplázate hacia abajo y marca la casilla "Subsistema de Windows para Linux", luego guarda, sal y reinicia tu computadora.

![photo_2022-06-10_14-44-13](https://user-images.githubusercontent.com/64184513/175776446-b373d0e5-4672-471f-a78a-93e0f2891313.jpg)

5. Abre VirtualBox y sigue las instrucciones de instalación.

6. Haz clic en "Archivo" en el menú, luego en "Herramientas" y elige "Gestor de paquetes de extensiones". Ahora haz clic en "Instalar" y luego elige el paquete de extensiones que descargaste.

![ext_pack_manager](https://user-images.githubusercontent.com/64184513/224564251-e4c33401-6178-4548-9737-b1d6af4fa85f.png)

7. Necesitarás un programa para extraer Kali del archivo .zip que descargaste.

Puedes descargarlo aquí: [7-zip](https://www.7-zip.org/download.html)

8. Una vez que 7zip esté instalado, abre tu carpeta de descargas y haz doble clic en el archivo .zip de Kali, crea una carpeta en tu escritorio y extrae su contenido en ella.

9. Ahora abre esta carpeta y haz doble clic en el archivo .vbox (el de color azul) y sigue las instrucciones.

![1](https://user-images.githubusercontent.com/64184513/196248353-103d6d04-bc9a-4e6d-96df-6a1fe4fb753c.png)

10. Haz clic en "Configuración" y, en "Sistema" / "Placa base", idealmente coloca al menos 4 GB de RAM, pero no sobrepases la línea roja. En "Orden de arranque", coloca "Disco duro" en primer lugar, luego "Óptico" y elimina "Disquete". Luego, en "Sistema" / "Procesador", coloca al menos 2 CPU, pero nuevamente no sobrepases la línea roja.

![4](https://user-images.githubusercontent.com/64184513/175776404-1eb16270-54d3-4d42-9741-2d2bbb0ce29b.jpg)
![5](https://user-images.githubusercontent.com/64184513/175776405-1227974e-c82f-4272-9b58-8163c14687e0.jpg)

11. En la sección "Red", configura la opción "Conectado a" en "Adaptador puente" y en "Avanzado", haz clic en las 2 flechas para aleatorizar la dirección MAC.

![7](https://user-images.githubusercontent.com/64184513/175776409-de0300c0-4908-4e94-ac28-6ac0e980f2b0.jpg)

12. Sal del panel de configuración.

13. Inicia Kali, llegarás a la pantalla de inicio de sesión:
```
Nombre de usuario: kali
Contraseña: kali
```
## ¡Felicidades, lo has logrado! Para continuar aprendiendo: [Aprendiendo Kali paso a paso con Self-Way](https://github.com/NeverWonderLand/Self-Way)
