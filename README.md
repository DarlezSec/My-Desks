## My Desktop Environments

A simple repository to show my desktop environments and the advances that I have in them... also how to configure them as I do.

---

### Gnome 41.2 + Debian 11 + Colloid Dark

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

   ![](https://github.com/DarlezSec/My-Desks/blob/main/gnome-shell-screenshot-3yrlxt.png)

---

### Colloid Theme

primero que nada aqui nos tendremos que crear una carpeta oculta llamada ".themes"

`mkdir .themes`

entraremos a la carpeta y clonaremos este repositorio de los temas

`git clone https://github.com/vinceliuice/Colloid-gtk-theme.git`

entraremos a la carpeta que nos dejo

`cd Colloid-gtk-theme`

ahora haremos un 

`./install.sh`

#### con esto ya estaria instalando el tema ahora solo tendriamos que ir a la aplicacion de retoques y poner el tema
#### aqui dejo un ejemplo de como lo tengo yo

![](https://github.com/DarlezSec/My-Desks/blob/main/Imagenes/gnome-shell-screenshot-gds5pl.png)

---

### Font que utilizo

la fuente que yo utilizo es la que utiliza la terminal de MacOS, este archivo de la font lo tienes que meter en una carpeta oculta llamada .fonts pasemos con una breve instalacion de ella..

![Font Menloo Regular](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbWxaZjU3WFBVNkZZQksxTG1LZDRjU0ZBR01IZ3xBQ3Jtc0tsR3g4RUNoLXVYMGthNVJSYW8yNDllSmh5NUdMRnhFVmcwcDRfMVdtb3E4NEpiQmdlcUdrVm1hbGM5LWYzODNjMFpIS3I0NWVpY1NfR3c1bF9MNFBZa2RqYldsZ21HQml4RllfQ05FZ3hYR1QxMURZOA&q=https%3A%2F%2Fgithub.com%2Fhbin%2Ftop-programming-fonts%2Fraw%2Fmaster%2FMenlo-Regular.ttf&v=o_KwUAu2s9w)

`mkdir .fonts`

la font se guardo por predeterminado en la carpeta de Descargas asi que hay que moverla

`cd Descargas`

`mv Menlo-Regular.ttf /home/users/.fonts/ .`

nos abriremos el archivo que guardabamos en la configuracion de kitty el archivo esta en la ruta de /home/users/.config/kitty/ y se llama "kitty.conf" asi ñes tuvo que quedar

![](https://github.com/DarlezSec/My-Desks/blob/main/Imagenes/gnome-shell-screenshot-hmbeim.png)

les dejare un post de mi pagina web sobre como editar y agregar valores a tu neofetch.


* ![Como agregar y cambiar los valores a tu configuracion de neofetch](https://darlezsec.vercel.app/p/modificar-y-agregar-valores-a-tu-neofetch/)







