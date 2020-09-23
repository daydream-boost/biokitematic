
[![Kitematic Logo](https://cloud.githubusercontent.com/assets/251292/5269258/1b229c3c-7a2f-11e4-96f1-e7baf3c86d73.png)](https://kitematic.com)

## biokitematic

this is a bioinfomatic version of [kitematic](https://github.com/docker/kitematic) base on bioconda.



![Kitematic Screenshot](https://cloud.githubusercontent.com/assets/251292/8246120/d3ab271a-15ed-11e5-8736-9a730a27c79a.png)

Kitematic is a simple application for managing Docker containers on Mac, Linux and Windows.


## Installing Kitematic

- Download Docker Desktop( win10 ) or Docker toolbox( win7, win8, win10 ) firstly
- registry-mirrors add "https://quay.io/"
- Download biokitematic and launch


## Uninstalling

**Mac**

- Remove Kitematic.app
- Remove any unwanted Virtual Machines in VirtualBox
```bash
# remove app data
rm -rf ~/Library/Application\ Support/Kitematic
```

**Windows**

Open `Programs and Features` from `Control Panel`

- Uninstall Kitematic
- Uninstall Oracle VM VirtualBox

## Copyright and License

Code released under the [Apache license](LICENSE).
Images are copyrighted by [Docker, Inc](https://www.docker.com/).
