<div align="center">

<a href="https://github.com/GrandKenzy">
  <img src="https://avatars.githubusercontent.com/u/136674533?v=4" alt="GrandKenzy" width="112" height="112" />
</a>

<h1>GrandKenzy</h1>

<strong>Building the tools behind the tools.</strong>

<p>Programming languages · Compilers · Developer infrastructure</p>

<a href="https://central.discentra.net"><img src="https://img.shields.io/badge/DISCENTRA-COMMUNITY-941F2C?style=for-the-badge" alt="Discentra Community" /></a>
<a href="https://github.com/GrandKenzy?tab=repositories"><img src="https://img.shields.io/badge/EXPLORE-PROJECTS-252525?style=for-the-badge&logo=github&logoColor=white" alt="Explore my repositories" /></a>

</div>

---

### Sobre mí

Desarrollo herramientas para **crear lenguajes, procesar código, gestionar dependencias y generar binarios**. Mi objetivo es construir un ecosistema de piezas independientes, reutilizables y bien documentadas, desde el lexer hasta la distribución de software.

Me interesan especialmente el **bajo nivel**, el diseño de compiladores, la arquitectura de sistemas, el rendimiento y las herramientas que dan mayor control a quienes programan.

<details>
<summary><strong>Read in English</strong></summary>

I build tools for **language design, parsing, dependency management and binary generation**. My goal is a modular developer ecosystem where every project is useful independently, but the components can also work together.

My main interests are **low-level programming**, compiler engineering, systems architecture, performance and developer experience.

</details>

### Proyectos principales

| Proyecto | Qué hace | Estado |
|:--|:--|:--|
| **[VNMA](https://github.com/GrandKenzy/vnma)** | Gestor de dependencias y vendoring para Python, con aislamiento de imports, instalaciones transaccionales y enlaces de desarrollo. | Beta |
| **[Gram](https://github.com/GrandKenzy/Gram)** | Framework de **lexer, parser combinators y AST**, con backtracking, sesiones y herramientas para DSL y lenguajes. | Beta 2.x |
| **[RIF](https://github.com/GrandKenzy/RIF)** | **Retargetable ISA Foundry**: define ISA, procesa MIR y emite binarios a nivel de bit sin depender de LLVM. | 1.0.0 |
| **[Bagron](https://github.com/GrandKenzy/EasyC)** | Lenguaje compilado y estáticamente tipado. Utiliza Gram; actualmente documenta un backend LLVM, con integración RIF como objetivo futuro. | En desarrollo |
| **[Packwire](https://github.com/GrandKenzy/packwire)** | Gestor de herramientas, compiladores y entornos de desarrollo para Windows, Linux y macOS. | Beta |
| **[Central](https://github.com/GrandKenzy/Central)** | Plataforma de **Discentra Community** para descubrir proyectos, documentación técnica y actividad de la comunidad. | En evolución |

### Cómo encajan

```text
                   ┌────────────────────┐
                   │  Bagron (language) │
                   └─────────┬──────────┘
                             │
                  ┌──────────▼──────────┐
                  │ Gram: lexer / AST   │
                  └──────────┬──────────┘
                             │
                  ┌──────────▼──────────┐
                  │ Bagron: semantics   │
                  │        & IR         │
                  └──────────┬──────────┘
                             │  planned
                  ┌──────────▼──────────┐
                  │ RIF: ISA / emitter  │
                  └──────────┬──────────┘
                             │
                        Native binary

       VNMA      → Python project dependencies
       Packwire  → Development tools & toolchains
       Central   → Documentation, projects & community
```

> **RIF ya funciona por separado:** admite definiciones `.rif` / `.pack` y MIR externo. La conexión **Bagron → RIF** es una dirección de desarrollo, no una capacidad anunciada como completada.

### Lo que estoy construyendo

- **Tooling modular:** componentes especializados con contratos claros y reutilización entre proyectos.
- **Compilación de bajo nivel:** ISA configurables, layouts binarios y control preciso de los bits.
- **Rendimiento y estabilidad:** benchmarks, pruebas de regresión, compatibilidad y reducción de trabajo innecesario.
- **Documentación accesible:** recursos en **español e inglés** para que otros puedan aprender y contribuir.

### Tecnologías con las que trabajo

<div align="center">

![Python](https://img.shields.io/badge/Python-222222?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-222222?style=flat-square&logo=c&logoColor=white)
![LLVM](https://img.shields.io/badge/LLVM-222222?style=flat-square&logo=llvm&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-222222?style=flat-square&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-222222?style=flat-square&logo=laravel&logoColor=white)
![React](https://img.shields.io/badge/React-222222?style=flat-square&logo=react&logoColor=white)
![Git](https://img.shields.io/badge/Git-222222?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-222222?style=flat-square&logo=linux&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-222222?style=flat-square&logo=windows&logoColor=white)

</div>

### Explora Discentra

<div align="center">

**[Discentra Community](https://central.discentra.net)** · **[Todos mis repositorios](https://github.com/GrandKenzy?tab=repositories)** · **[RIF: ejemplos AMD64 / ELF64](https://github.com/GrandKenzy/RIF/tree/main/examples)**

<sub>Build. Understand. Improve. Repeat.</sub>

</div>