#osintV13

██╗░░░██╗██╗███████╗██████╗░███╗░░██╗███████╗███████╗░░███╗░░██████╗░
██║░░░██║██║██╔════╝██╔══██╗████╗░██║██╔════╝╚════██║░████║░░╚════██╗
╚██╗░██╔╝██║█████╗░░██████╔╝██╔██╗██║█████╗░░░░███╔═╝██╔██║░░░█████╔╝
░╚████╔╝░██║██╔══╝░░██╔══██╗██║╚████║██╔══╝░░██╔══╝░░╚═╝██║░░░╚═══██╗
░░╚██╔╝░░██║███████╗██║░░██║██║░╚███║███████╗███████╗███████╗██████╔╝
░░░╚═╝░░░╚═╝╚══════╝╚═╝░░╚═╝╚═╝░░╚══╝╚══════╝╚══════╝╚══════╝╚═════╝░
Busqueda automatica de informacion de personas en chile. Basado en web scrapping y algunas cosillas mas<br>
## Disclaimer:
Este script es solo para propositos educativos y para poner en la mesa el tema de la privacidad de los datos<br>
¿que tan protegidos estan los datos que le entregas a las empresas?<br>
<br>
## Como lo Uso: <br>
  Sin parametros te muestra una ayuda<br>
<br>
$ python3 osintV13.py<br>
usage: osintV13 [-h] [-rut [RUT]] [-patente [PATENTE]]<br>
                  [-telefono [TELEFONO]]<br>

Busqueda automatica en fuentes abiertas (y no tan abiertas) de chile<br>
<br>
optional arguments:<br>
  -h, --help            show this help message and exit<br>
  -rut [RUT]            Rut de la persona a buscar, con formato: 11111111-1<br>
  -patente [PATENTE]    Patente del vehiculo a buscar, con formato: aabb11<br>
  -telefono [TELEFONO]  telefono a buscar, con formato: 56999999999<br>
<br>
<br>
Ejemplos<br>
$python3 osintV13.py -rut 3198442-4<br>
$python3 osintV13.py -telefono 56955555555<br>
$python3 osintV13.py -patente aabb11<br>

