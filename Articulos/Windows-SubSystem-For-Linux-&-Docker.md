---
title: "WSL2"
metaTitle: "WSL2"
metaDescription: "WSL2 Linux"
---


Windows Subsystem for linux, permite usar linux desde dentro de windows, traduciendo las llamadas que hace linux al kernel, al propio kernel de windows.


La versión 2 de WSL, mejora la velocidad debido a la virtualización del kernel de linux dentro del core de windows, obteniendo una velocidad más significativa.


## Requisitos
Para poder instalar WSL2 se debe tener un Windows 10 a partir del build 2004

## Paso1, Instalación de WSL2.
Lo primero es agregar los programas necesarios en windows desde la instalación de programas, para llegar directamente, usar el comando `appwiz.cpl` desde ejecutar.

![image.png](/.attachments/image-94ded8d2-0a9b-4b7a-8bf0-1ce127a59e0d.png)


![image.png](/.attachments/image-b48414d4-7c21-4345-ae85-5348df4357a9.png)

##Paso 2, Instalar la versión de linux de su opción.

- [Ubuntu 16.04 LTS](https://www.microsoft.com/store/apps/9pjn388hp8c9)
- [Ubuntu 18.04 LTS](https://www.microsoft.com/store/apps/9N9TNGVNDL3Q)
- [Ubuntu 20.04 LTS](https://www.microsoft.com/store/apps/9n6svws3rx71)
- [openSUSE Leap 15.1](https://www.microsoft.com/store/apps/9NJFZK00FGKV)
- [SUSE Linux Enterprise Server 12 SP5](https://www.microsoft.com/store/apps/9MZ3D1TRP8T1)
- [SUSE Linux Enterprise Server 15 SP1](https://www.microsoft.com/store/apps/9PN498VPMF3Z)
- [Kali Linux](https://www.microsoft.com/store/apps/9PKR34TNCV07)
- [Debian GNU/Linux](https://www.microsoft.com/store/apps/9MSVKQC78PK6)
- [Fedora Remix for WSL](https://www.microsoft.com/store/apps/9MSVKQC78PK6)
- [Pengwin](https://www.microsoft.com/store/apps/9NV1GV1PXZ6P)
- [Pengwin Enterprise](https://www.microsoft.com/store/apps/9N8LP0X93VCP)
- [Alpine WSL](https://www.microsoft.com/store/apps/9p804crf0395)


![image.png](/.attachments/image-2f275406-39f1-4328-b44e-844157a5d53b.png)


## Paso3, Configurar una nueva distribución.
La primera vez que ejecute la nueva distribución instalada, una consola se abrirá y le pedirá que espero por un minuto o dos, para descomprimir y almacenar en su PC. 

En ese momento debe crear su usuario y password.


![image.png](/.attachments/image-bc74c13d-2a7d-444a-84da-64ee4a749955.png)

##Paso3, Configurando su distribución a WSl2.

La instalación por defecto lo hace con WSL1, lo podemos comprobar con el siguiente comando

```
wsl --list --verbose
``` 

![image.png](/.attachments/image-85233501-5b29-4eda-9c44-caf6c172aef8.png)


Para cambiar a Wsl2 tenemos dos opciones.

1. Configurar indivisualmente `wsl --set-version <distribution nama> <versionNumber>`
2. Configurar todas las distribuciones `wsl --set-default-version 2`


Una vez instalado solo queda instalar [Docker](https://hub.docker.com/editions/community/docker-ce-desktop-windows/)

<IMG  src="https://hackernoon.com/photos/g6XLgq1iVUY99RSvUwyulTe0TAM2-qnhj3wjh"/>


