# Pcap Reader Beta

Es un pequeño programa para poder leer de forma rápida el contenido de los pcap. 

Aún tiene cosas por revisar como el encode de los payload porque muestra caracteres que no reconoce pero es un vistazo rápido.

Para ejecutarlo hay que hacer lo siguiente: 

Instalamos las librerías: 

```
go mod tidy

```

Una vez instaladas ejecutamos pasando como parametro el archivo que queremos analizar: 

```
go run main.go /home/drakorod/SpeedyMovil/Peru/200_108_104_125_001.pcap
```

Si queremos meterlo en un archivo deberemos de utilizar el siguiente comando para linux

```
go run main.go /home/drakorod/SpeedyMovil/Peru/200_108_104_125_001.pcap > trazas.xml
```