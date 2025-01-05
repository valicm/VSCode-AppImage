<h2 align="center">Zed AppImage</h2>
<p align="center">Unofficial / Community provided Zed AppImage - stable release</p>

[![Zed AppImage release](https://github.com/lavilao/Zed-AppImage/actions/workflows/release.yml/badge.svg?branch=main)](https://github.com/lavilao/Zed-AppImage/actions/workflows/release.yml)

## Get Started

#### [Download the latest stable release](https://github.com/lavilao/Zed-AppImage/releases/latest)
- stable release only
- supports update of the AppImage

### Executing
#### File Manager
Double-click the `*.AppImage` file and you are done!

> In normal cases, the above method should work, but in some cases you 
> need mark file as executable. You can do this using File manager -> right click > Properties > Allow Execution,
> or by terminal issuing command `chmod +x Zed-*.AppImage`

#### Appimaged
Use Appimaged for better desktop integration ==> [download appimaged](https://github.com/probonopd/go-appimage/tree/master/src/appimaged)

#### Terminal
```bash
chmod +x Zed-*.AppImage
./Zed-*.AppImage
```

#### Official source code
The official source code of the Zed is available at links provided
https://github.com/zed-industries/zed

#### Build
The AppImage is built from .tar.gz Zed package by GitHub Continuous Integration using this
bash script https://github.com/lavilao/appimage-bash.
