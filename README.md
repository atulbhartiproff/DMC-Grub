![DantePreview](DantePreview.jpg?raw=true)

## Prerequisites

Use your preferred package managers to install the following packages

```sh
sudo pacman -S magick inkspace optipng
```

## Installation:

Create icons with:
```sh
cd assets
./render-all.sh
```

Usage:  

```sh
sudo ./install.sh`
```

### Extra Options:
 - Install dante theme on 2k display device:

```sh
sudo ./install.sh -t dante -s 2k
```

 - Install vergil theme into /boot/grub/themes:

```sh
sudo ./install.sh -b -t vergil
```

 - Uninstall dante theme:

```sh
sudo ./install.sh -r -t dante
```


## Documents

[Grub2 theme reference](https://wiki.rosalab.ru/en/index.php/Grub2_theme_/_reference)

[Grub2 theme tutorial](https://wiki.rosalab.ru/en/index.php/Grub2_theme_tutorial)

[Inspiration](https://github.com/vinceliuice/Wuthering-grub2-themes)
