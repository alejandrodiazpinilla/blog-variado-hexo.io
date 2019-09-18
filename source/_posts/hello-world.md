---
title: Install Ruby 
---

### apt (Debian o Ubuntu)

Debian GNU/Linux y Ubuntu usan el gestor de paquetes apt. Se usa de la siguiente manera:

``` bash
$ sudo apt-get install ruby-full
```

Al momento de escribir este documento, el paquete ruby-full instala la versión de Ruby 2.3.1, la cual es una entrega vieja pero estable en Debian y Ubuntu.

yum (CentOS, Fedora, or RHEL)
CentOS, Fedora, y RHEL usan el gestor de paquetes yum. Se usa de la siguiente manera:


``` bash
$ sudo yum install ruby
```


La versión instalada es típicamente la versión de Ruby disponible en el momento de liberación de la versión específica de cada distribución.

portage (Gentoo)
Gentoo usa el gestor de paquetes portage.

``` bash
$ sudo emerge dev-lang/ruby
```


Por defecto, este comando va a tratar de instalar las versiones 1.9 y 2.0, pero existen más versiones disponibles. Para instalar una versión específica, establece RUBY_TARGETS en el archivo make.conf. Para obtener más detalles puedes leer el sitio de el Gento Ruby Project.

### pacman (Arch Linux)

Arch Linux usa el gestor de paquetes llamado pacman. Para instalar Ruby, solamente tienes que hacer esto:
 
``` bash
$ sudo pacman -S ruby
```

Esto debería instalar la última versión estable de Ruby.

### Homebrew (macOS)

Ruby 2.0 ya viene instalado en OS X El Capitan, Yosemite, Mavericks y macOS Sierra. OS X Mountain Lion, Lion, y Snow Leopard vienen con Ruby 1.8.7 instalado.

Algunas personas en macOS usan Homebrew como gestor de paquetes. Es muy fácil obtener una versión nueva de Ruby usando Homebrew:
 
``` bash
$ brew install ruby
```
