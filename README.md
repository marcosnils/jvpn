##Prerequisites

Make sure your OS can execute 32 bit binaries. If you're using ubuntu 14.04 or newer you should run:

sudo dpkg --add-architecture i386  
sudo apt-get update  
sudo apt-get install libc6:i386 libncurses5:i386 libstdc++6:i386 lib32z1  

###ReadTerm perl module

sudo apt-get install libterm-readkey-perl


##Config

Abrir el archivo `jvpn.ini`y modificar los siguientes parámetros:

`host` - Host de la VPN (ej: legolas.mexxxxxxxxx.com o cerbero.mexxxxxxxxx.com)

`realm` - El Real requerido.  ej. Users (SFA)

`username` - Nombre de usuario

`password` - Contraseña. Puede utilizarse la opción `plaintext:$pass` Donde `$pass` es la contraseña (__el password se guarda en texto plano y no se encripta__).

La opción `interactive` permite ingresar los valores al momento del ejecutar el script. 


##Run

```
sudo ./jvpn.pl
```
