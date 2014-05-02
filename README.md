##Config

Abrir el archivo `jvpn.ini`y modificar los siguientes parámetros:

`host` - Host de la VPN (ej: legolas.mexxxxxxxxx.con o cerbero.mexxxxxxxxx.com)

`realm` - El Real requerido.  ej. Users (SFA)

`username` - Nombre de usuario

`password` - Contraseña. Puede utilizarse la opción `plaintext:$pass` Donde `$pass` es la contraseña (__el password se guarda en texto plano y no se encripta__).

La opción `interactive` permite ingresar los valores al momento del ejecutar el script. 


##Run

```
sudo ./jvpn.pl
```
