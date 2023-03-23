# ProjectManager

## requirements:
- nodejs
- npm 
- php
- composer 

## Architecture
```
├── DEBIAN
│   └── control
└── usr
    ├── bin
    │   └── project_manager.sh
    └── share
        ├── applications
        │   └── project_manager.desktop
        └── icons
            └── icon.png
```
## Install
- Download the .deb package
```bash
sudo dpkg -i projectManager.deb
```
- Use the following command to install the package : 

```bash
project_manager.sh
```

## Uninstall
```bash
sudo apt-get remove project-manager 
```