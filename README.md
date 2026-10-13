# Mi Proyecto
![build](https://img.shields.io/badge/build-passing-brightgreen)
![license](https://img.shields.io/badge/license-MIT-blue)
![version](https://img.shields.io/badge/version-1.0.0-orange)

## Tabla de contenidos
- [Instalación](#instalación)
- [Uso](#uso)
- [Arquitectura](#arquitectura)
- [Contribuidores](#contribuidores)

## Tecnologías
| Tecnología | Versión | Propósito          |
| ---------- | ------- | ------------------ |
| Node.js    | 18.x    | Servidor backend    |
| React      | 18.x    | Interfaz de usuario |
| MongoDB    | 6.x     | Base de datos       |


## Arquitectura
```mermaid
flowchart LR
  Cliente -->|HTTPS| API
  API -->|SQL| BaseDeDatos
  API -->|JWT| ServicioAuth
```

## Capturas
![Vista principal](/Captura%20de%20pantalla%202026-10-13%20a%20la(s)%2012.34.38 a.m..png)

## Contribuidores
- [@tu-usuario](https://github.com/mateoazabache-art) — Desarrollo y documentación
