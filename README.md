## My Desktop Environments

A simple repository to show my desktop environments and the advances that I have in them... also how to configure them as I do.

---

### Gnome 41.2 + Debian 11 

![](https://github.com/DarlezSec/My-Desks/blob/main/Captura%20de%20pantalla%20de%202022-05-24%2019-44-19.png)

---

### Instalacion de mi config 

### Kitty

| Distro | Install Command |
| :----: | :----: |
| ![Fedora] | `sudo dnf install kitty` |
| ![Debian]&nbsp;![Ubuntu] | `sudo apt install kitty` |
| ![Gentoo] | `sudo emerge -a kitty` |

[arch]: https://antergos.com/distro-logos/archlogo26x26.png
[fedora]: https://user-images.githubusercontent.com/17854950/86288769-c3351a00-bbea-11ea-908c-156c7bf0b778.png
[openSUSE]: https://antergos.com/distro-logos/Geeko-button-bling7.png
[ubuntu]: https://user-images.githubusercontent.com/17854950/86288823-e069e880-bbea-11ea-9214-4764c5628f39.png
[debian]: https://user-images.githubusercontent.com/17854950/86288828-e4960600-bbea-11ea-9a46-4eb19621b3ae.png
[gentoo]: https://user-images.githubusercontent.com/17854950/86288836-e790f680-bbea-11ea-8104-3aa429805d0e.png

Con la terminal ya instalada ahora aplicaremos el tema en la terminal:D

Entraremos a la carpeta .config/kitty/

`cd .config/kitty/`

en esta carpeta oculta normalmente se guardan los paquetes de tercera persona

Comenzamos clonando el repositorio donde esta mi configuracion

`git clone https://github.com/DarlezSec/My-Desks.git`

ahora entraremos con 

`cd My-Desks`

moveremos los archivos al directorio anterior

`mv kitty.conf color.ini ..`
