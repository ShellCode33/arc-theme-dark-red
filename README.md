# Arc Theme Dark Red Edition

Tested against GTK 3 and GTK 4 only. Only the `dark` variant is supported.

![A screenshot of the Arc theme dark red edition](https://raw.githubusercontent.com/ShellCode33/arc-theme-dark-red/master/.github/arc-theme-dark-red.png)

## Build

```
meson setup --prefix=$HOME/.local -Dthemes=gtk3,gtk4 -Dvariants=dark build/
meson install -C build/
load-gtk-conf
```

You can use `gtk4-widget-factory` to test your changes.
