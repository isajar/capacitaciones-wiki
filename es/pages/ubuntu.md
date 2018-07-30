# Ubuntu

## Ubuntu troubleshooting 

### Lost wifi connection Ubuntu 16.04

* **Descripcion:**  Se pierde la deteccion de redes wifi despues de instalar ciertas actualizaciones
* **Solucion:**  Reinstalar los drivers de la placa de red
  * `sudo apt-get purge bcmwl-kernel-source`
  * `wget http://mirrors.kernel.org/ubuntu/pool/restricted/b/bcmwl/bcmwl-kernel-source_6.30.223.271+bdcom-0ubuntu4_amd64.deb`
  * `sudo dpkg -i bcmwl-kernel-source_6.30.223.271+bdcom-0ubuntu4_amd64.deb`
* **Links:** 
  * https://ubuntuforums.org/showthread.php?t=2397051
  * https://askubuntu.com/questions/55868/installing-broadcom-wireless-drivers