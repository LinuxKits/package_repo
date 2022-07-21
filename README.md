# package_repo
A place to store all background that packed in .ctpkg format
# Usage:

Install ctpkg in your system first

(ctpkg)[https://ruzhtw.top/CtPKG]

then add this source in /etc/centerlinux/conf.d/ctpkg.source

```
[distro_wallpaper]https://github.com/LinuxKits/package_repo/releases/download/ctpm/
```

and

```
ctpkg upd
ctpkg grab l | grep distro_wallpaper/ 
```

