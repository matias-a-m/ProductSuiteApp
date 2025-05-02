# ProductSuiteApp

**Aplicación contenedora que integra y demuestra el funcionamiento del sistema modular de desarrollo iOS.**

`ProductSuiteApp` funciona como el dashboard técnico del portfolio. No es solo una app de ejemplo: es una guía navegable que conecta cada módulo y framework, mostrando cómo las decisiones de arquitectura, diseño visual y seguridad interactúan en un entorno real.

---

## Propósito

- Visualizar la integración real de los módulos técnicos y frameworks base.
- Ofrecer un entorno de prueba vivo para experimentar con animaciones, layouts, flujos de datos y mecanismos de seguridad.
- Actuar como punto de entrada al sistema modular y su documentación.
- Servir como guía de buenas prácticas en la composición de productos digitales nativos.

---

## Contenido

- **Navegación técnica** entre módulos mediante `SwiftUI`.
- **Vistas demostrativas** para cada framework: animaciones, tokens, validaciones, seguridad.
- **Interacción real** con lógica compartida (`FoundationKit`), componentes (`InterfaceKit`) y efectos visuales (`MotionKit`).
- **Aplicación de seguridad contextual** usando `SecurityKit`.

---

## Estructura de navegación

```
ProductSuiteApp/
├── App/
│   ├── ProductSuiteApp.swift
│   └── Router.swift
├── Features/
│   ├── MotionShowcase/
│   ├── UXPatterns/
│   ├── ArchitectureDemo/
│   ├── SecureFlows/
│   └── DataResilience/
├── Shared/
│   ├── Components/
│   ├── Theme/
│   └── Utilities/
```

---

## Frameworks integrados

| Framework        | Función dentro de la app                          |
|------------------|---------------------------------------------------|
| `FoundationKit`  | Validaciones, extensiones de formato, helpers     |
| `InterfaceKit`   | Tokens visuales, layouts responsivos, UI shared   |
| `MotionKit`      | Animaciones contextuales, transiciones, háptico   |
| `SecurityKit`    | Flujos de cifrado, autenticación y privacidad     |

---

## Módulos técnicos demostrados

| Módulo técnico     | Propósito en la app                                      |
|--------------------|-----------------------------------------------------------|
| `MotionStudio`     | Demostración de microinteracciones nativas                |
| `ArchitectureBench`| Navegación entre arquitecturas aplicadas a un mismo flujo |
| `UXBlueprints`     | Uso de patrones de experiencia nativa en SwiftUI          |
| `DataFlowLab`      | Escenarios con `async/await`, estado y resiliencia        |

---

## Enfoque de pruebas

`ProductSuiteApp` incluye pruebas funcionales básicas que validan la integración y navegación:

| Área                  | Tipo de prueba                     |
|-----------------------|------------------------------------|
| Rutas y enlaces       | Navegación entre módulos           |
| Vistas principales    | Renderizado, jerarquía visual      |
| Flujos de datos       | Consistencia entre estados         |
| Interacciones         | Validación visual y de feedback    |

Las pruebas pueden extenderse con `XCTest`, `SnapshotTesting` o `XCUITest` si se requiere.

---

## Requisitos

- iOS 15+
- Swift 6
- Xcode 15+
- Swift Package Manager

---

## Instalación

1. Clonar el repositorio:  
   ```bash
   git clone https://github.com/matias-a-m/ProductSuiteApp.git
   ```
2. Abrir el proyecto con Xcode (`ProductSuiteApp.xcodeproj` o `.xcworkspace` si aplicara).
3. Esperar la resolución de dependencias de Swift Package Manager.
4. Ejecutar la app en un simulador o dispositivo real con iOS 15+.

---

## Licencia

MIT © [Matías Adrián Molina](mailto:matias.a.molina87@icloud.com)
