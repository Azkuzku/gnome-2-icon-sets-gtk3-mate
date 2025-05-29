# Gnome Legacy Icon Theme

I am using this on a GTK2 desktop (Xfce 4.12). GTK3 programs may have a
problem with icons other than 48x48 and 16x16.

Based on:
* [gnome-icon-theme 2.14.2](https://download.gnome.org/sources/gnome-icon-theme/2.14/)
* [Old GNOME2 Icon Theme](https://www.deviantart.com/eqlovelace/art/Old-GNOME2-Icon-Theme-192943815)
* [gPerfection2](https://github.com/GarthTheChicken/gperfection2)
* [Archive](https://download.gnome.org/teams/art.gnome.org/archive/themes/icon/): ICON-Ximian-North, gnome-rh8, SmoothGNOME

# mime-custom

Custom mime settings. Among the additions are:
* README.md
* FASTA files
* h5ad
* seurat

Place `custom.xml` in `/usr/share/mime/packages`, after which run:

```
update-mime-database /usr/share/mime
```
