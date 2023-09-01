## Configuraciones del Sistema
En este archivo se describen las configuraciones realizadas al sistema operativo para su utilización 

#### Sistema instalado
Luego de realizar varias pruebas de funcionalidad con el sistema operativo descargado de la página del fabricante de la placa Jetson Nano y de realizar pruebas con conda, se decidió reinstalar un sistema operativo preconfigurado por [Q-engineering](https://qengineering.eu/install-opencv-on-jetson-nano.html). La documentación de la imagen instalada se pueden encontrar en [https://github.com/Qengineering/Jetson-Nano-image](https://github.com/Qengineering/Jetson-Nano-image).

#### Cámara
Documentación del driver instalado en [https://docs.arducam.com/Nvidia-Jetson-Camera/Native-Camera/Quick-Start-Guide/](https://docs.arducam.com/Nvidia-Jetson-Camera/Native-Camera/Quick-Start-Guide/)

##### Pruebas de la camara
**Prueba 1**
```
sudo apt-get 
sudo apt-get install v4l-utils
v4l2-ctl --list-formats-ext
```

**Prueba 2**
Se realizaron las pruebas indicada por [JetsonHacks](https://jetsonhacks.com/about-us/) en su publicación [CSI-Camera](https://github.com/JetsonHacksNano/CSI-Camera)



