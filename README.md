# Nombre repo

![Python](https://img.shields.io/badge/python-3.12+-orange?logo=python&logoColor=white) 
![NixOS](https://img.shields.io/badge/NixOS-blue?logo=nixos&logoColor=white&color=5277C3)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?logo=sqlite&logoColor=white)
![Version](https://img.shields.io/badge/version-0.1--alpha-blue)
[![License: GPL v3](https://img.shields.io/badge/license-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
![Last Commit](https://img.shields.io/github/last-commit/neko-nix/repo-plantilla)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/neko-nix/repo-plantilla)
![GitHub issues](https://img.shields.io/github/issues/neko-nix/repo-plantilla?color=informational)


[DESCRIPCIÓN GENERAL REPO]

## Funciones actuales
- [x]
- [x]
## Funciones planeadas
- [ ]
- [ ]
## Entorno en NixOS
Para activar el entorno de desarrollo, descargando e instalando todas sus dependencias, se requiere utilizar NixOS, y ejecutar el siguiente comando estando en el directorio del proyecto:
```sh
nix develop
```

## Estructura del proyecto:
```text
├── data                # Bases de datos
├── scripts             # Scripts sueltos que hagan cosas puntuales fuera de la aplicación en si misma
├── src                 # Núcleo de la aplicación
│   └── nombreApp       # Nombre de la app, así es más intuitivo llamarla, tipo `python -m src.nombreApp.core.dataAnalysis` o qué sé yo
│       ├── core        # Donde están las cosas importantes de la app.
│       └── utils       # Módulos extra que se llaman desde `core`. La idea es que estos sean independientes y puedan funcionar en otros proyectos.
└── tests               # Espejo del `src` para hacer pruebas
```

## Licencia
Este proyecto está bajo la licencia GNU GENERAL PUBLIC LICENSE V3. Consulta el archivo [LICENSE](LICENSE) para más detalles.