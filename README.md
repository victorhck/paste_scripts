Este repositorio contiene unas versiones modificadas por mí de los scripts _susepaste_ y _susepaste-screenshot_ que ofrece openSUSE en `/usr/bin/` y que están disponibles en este repositorio de openSUSE:
* [https://github.com/openSUSE/paste/tree/master/script](https://github.com/openSUSE/paste/tree/master/script)

Los scripts sirven para subir un texto o una imagen de nuestro equipo al [servicio paste de openSUSE](https://susepaste.org)

## Modificaciones realizadas:
* Añadir en la opción de expiración un diálogo más amigable basado en minutos, horas, días, meses, años:

`30m = 30 minutos; 1h = 1 hora; 6h = 6 horas; 12h = 12 horas; 1d = 1días; 1w = 1 semana; 1m = 1 mes; 3m = 3 meses; 1y = 1 año; 2y = 2 años; 3y = 3 años; 0 = nunca`
* Añadir la opción -h para mostrar la ayuda del script
* Añadir la opción -d [seg] para añadir un _delay_ a la hora de tomar una captura de pantalla con _susepaste-screenshot_.
* Solucionar error al copiar el texto al portapapeles del sistema

## Instalación

Simplemente copiar los scripts en la ruta `/usr/bin/` renombrando primero los anteriores, si queremos volver a atrás.
