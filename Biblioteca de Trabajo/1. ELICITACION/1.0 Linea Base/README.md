# Líneas Base del Proyecto MinGO

Las líneas base representan puntos de referencia formales en la evolución del proyecto, conteniendo versiones aprobadas de los artefactos de configuración.

## Resumen de Líneas Base

| **Código** | **Nombre Línea Base** | **Descripción**                          | **Fecha de Establecimiento** | **Estado** | **Responsables**                             |
| ---------- | --------------------- | ---------------------------------------- | ---------------------------- | ---------- | -------------------------------------------- |
| LBA        | Análisis              | Documentos de la fase de análisis        | 08/01/2026                   | Activa     | Marcos Escobar, Mateo Sosa, Fernando Tipán   |
| LBC        | Implementación        | Código fuente del desarrollo             | 08/01/2026                   | Activa     | Marcos Escobar, Mateo Sosa, Fernando Tipán   |
| LBD        | Diseño                | Diagramas y documentos de diseño         | 08/01/2026                   | Activa     | Marcos Escobar, Mateo Sosa, Fernando Tipán   |
| LBR        | Requisitos            | Especificación de requisitos del sistema | 08/01/2026                   | Activa     | Marcos Escobar, Mateo Sosa, Fernando Tipán   |

## Descripción del Sistema de Líneas Base

El proyecto MinGO utiliza un esquema de 4 líneas base para gestionar la configuración del software:

- **LBA (Análisis):** Contiene artefactos de análisis como diagramas de actividades y documentación de procesos
- **LBC (Código):** Almacena el código fuente de la aplicación móvil (MinGO_App) y la API (MinGO_API)
- **LBD (Diseño):** Incluye diagramas de flujo, arquitectura y diseño del sistema
- **LBR (Requisitos):** Contiene documentos SRS y diagramas de casos de uso

## Estructura de Carpetas

```
1.0 Linea Base/
├── LBA/                # Línea Base de Análisis
│   └── MinGO Activity.pdf
├── LBC/                # Línea Base de Código
│   ├── MinGO_App/      # Aplicación móvil Flutter
│   └── MinGO_API/      # Backend API
├── LBD/                # Línea Base de Diseño
│   └── MinGO Flujo.pdf
└── LBR/                # Línea Base de Requisitos
    ├── G4_27835_SRS_ADS_V2.0.pdf
    └── DCU_MinGO_v1.0.pdf
```

## Historial de Cambios

| **Fecha**   | **Descripción del Cambio**                          | **Autor**   |
| ----------- | --------------------------------------------------- | ----------- |
| 08/01/2026  | Establecimiento inicial de las 4 líneas base        | Equipo G4   |
| 12/01/2026  | Actualización de contenido en LBA, LBC, LBD         | Equipo G4   |
| 15/01/2026  | Adición de DCU a LBR                                | Equipo G4   |

## Control de Configuración
- **Verificado por:** Mateo Sosa (Gestor de Configuración)
- **Fecha de verificación:** 25/01/2026
- **Estado:** Integridad de líneas base verificada
- **Observación:** Todas las líneas base cumplen con los estándares definidos en el PGS
