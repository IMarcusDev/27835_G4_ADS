# Línea Base LBC - Implementación (Código)

Línea base que contiene todo el código fuente del proyecto MinGO, incluyendo la aplicación móvil y la API backend.

## Versiones y Variantes

| **Código del ECS** | **Nombre completo del ECS** | **Autor(es) del artefacto**              | **Ruta en el repositorio Git**                                            | **Línea base a la que pertenece** | **Tipo de ECS** | **Fecha de creación** | **Última fecha de modificación** |
| ------------------ | --------------------------- | ---------------------------------------- | ------------------------------------------------------------------------- | --------------------------------- | --------------- | --------------------- | -------------------------------- |
| APP                | MinGO App                   | Marcos Escobar, Mateo Sosa, Fernando Tipán | 27835_G4_ADS/Biblioteca de Trabajo/1. ELICITACION/1.0 Linea Base/LBC/MinGO_App/ | LBC                               | Código          | 12/01/2026            | 12/01/2026                       |
| API                | MinGO API                   | Marcos Escobar, Mateo Sosa, Fernando Tipán | 27835_G4_ADS/Biblioteca de Trabajo/1. ELICITACION/1.0 Linea Base/LBC/MinGO_API/ | LBC                               | Código          | 12/01/2026            | 12/01/2026                       |

## Descripción del Artefacto

La Línea Base de Código contiene:
- **MinGO_App:** Aplicación móvil desarrollada en Flutter
  - Interfaces de usuario
  - Servicios y contextos para la lógica de la aplicación
  - Configuraciones del proyecto (pubspec.yaml, etc.)
- **MinGO_API:** Backend del sistema
  - Endpoints REST
  - Lógica de negocio del servidor

## Estructura

```
LBC/
├── MinGO_App/          # Aplicación móvil Flutter
│   ├── lib/            # Código fuente Dart
│   ├── ios/            # Configuración iOS
│   ├── android/        # Configuración Android
│   └── ...
└── MinGO_API/          # Backend API
    └── ...
```

## Historial de Cambios

| **Versión** | **Fecha**   | **Descripción del Cambio**                         | **Autor**   |
| ----------- | ----------- | -------------------------------------------------- | ----------- |
| V1.0        | 12/01/2026  | Versión inicial del código fuente en línea base    | Equipo G4   |

## Responsables

Marcos Escobar, Mateo Sosa, Fernando Tipán

## Control de Configuración
- **Verificado por:** Mateo Sosa (Gestor de Configuración)
- **Fecha de verificación:** 26/01/2026
- **Estado:** LBC conforme a estándares de código

## Auditoría de Calidad (SQA)
- **Auditado por:** Fernando Tipán (Responsable SQA)
- **Fecha de auditoría:** 26/01/2026
- **Cumplimiento de estándares:** Cumple
- **Observaciones:** Código fuente versionado correctamente