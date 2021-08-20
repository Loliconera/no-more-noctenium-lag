## No más retraso de Noctenium
Módulo Tera-Proxy para Tera Online. Bloquea los paquetes que causan retrasos en el cliente al usar Noctenium.
### Problemas conocidos
* La cantidad de Noctenium del lado del cliente no se actualizará en combate hasta que abras tu inventario o te quedes sin Noctenium.
* Projectile skills (especialmente gunner's Arcane Barrage y Mana Missiles) se retrasan en el lado del servidor cuando noctenium está activo. Tener más noctenium en su inventario empeora esto. Debido a que esto es del lado del servidor, no hay solución. :(
* Dar el último golpe a un achievement mob/boss mientras se usa Noctenium puede retrasar el desbloqueo de logros del lado del cliente. Consumir cualquier consumible en tu inventario, avanzar en un tipo diferente de logro o volver a registrar tu personaje debería solucionar este problema.
### Requisitos
[Tera-Proxy](https://github.com/tera-toolbox/tera-toolbox) y dependencias
