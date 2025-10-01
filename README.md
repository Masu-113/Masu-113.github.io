<!-- Logo del proyecto -->
<p align="center">
  <img src="https://github.com/Masu-113/NetPort-Configurator/blob/main/src/assets/LogoNetPot.png" alt="NetPort Configurator Logo" width="350">
</p>

---

<h1 align="center">NetPort Configurator</h1>

<p align="center">
  Aplicación de escritorio para <b>Windows</b> desarrollada con <b>Tauri</b> y <b>HTML/CSS/JavaScript</b> para visualizar y modificar configuraciones de puertos de red.
</p>

<!-- Badges -->
<p align="center">
  <a href="https://www.microsoft.com/es-es/windows" target="_blank">
    <img src="https://img.shields.io/badge/Plataforma-Windows-blue?style=flat-square" alt="Windows">
  </a>
  <a href="https://tauri.app/start/" target="_blank">
    <img src="https://img.shields.io/badge/Tauri-v2.x-orange?style=flat-square" alt="Tauri v2">
  </a>
  <a href="https://github.com/Masu-113/NetPort-Configurator/blob/main/LICENSE" target="_blank">
    <img src="https://img.shields.io/badge/Licencia-MIT-green?style=flat-square" alt="Licencia">
  </a>
  <img src="https://img.shields.io/badge/Estado-En%20Desarrollo-yellow?style=flat-square" alt="Estado">
</p>

---

## Tabla de contenido

1. [Introducción](#netport-configurator)
2. [Características](#características)
3. [Requisitos previos](#requisitos-previos)
4. [Instalación para desarrollo](#instalación-para-desarrollo)
5. [Modificar Iconos de la Aplicación](#modificar-iconos-de-la-aplicacion)
6. [Recomendaciones de uso](#recomendaciones-de-uso)
7. [Compilación para distribución](#compilación-para-distribución)
8. [Instaladores](#instaladores)
9. [Notas sobre la aplicación](#notas-sobre-la-aplicacion)
10. [Estructura del Proyecto](#estructura-del-proyecto)
11. [Changelog](#changelog)
12. [Créditos](#creditos)
13. [Donaciones](#donaciones)

---

## NetPort Configurator

Aplicación de escritorio para **Windows**, desarrollada con **Tauri** y **HTML/CSS/JavaScript**, diseñada para visualizar y modificar configuraciones de puertos de red de manera sencilla a través de una interfaz gráfica.

Esta herramienta permite a los administradores y técnicos de redes cambiar rápidamente parámetros clave como:

- **VLAN ID**
- **Dirección IP**
- **Máscara de subred**
- **Puerta de enlace**
- **DHCP**

Incluye scripts **PowerShell (.ps1)** integrados que se ejecutan con permisos elevados para realizar las configuraciones directamente en el sistema.

---

## Características

- Visualización de puertos de red disponibles en el equipo.
- Configuración rápida de VLAN ID, IP, máscara y gateway.
- Integración con scripts `.ps1` para aplicar cambios.
- Ejecución con permisos elevados mediante acceso directo configurado con `runas`.
- Interfaz gráfica ligera y optimizada con HTML/CSS/JS.
- Compatible con **Windows 10/11** (soporte para Linux/Mac con adaptación de scripts).

---

## Requisitos previos

Antes de ejecutar o compilar el proyecto, asegúrate de tener instalado:

| Requisito          | Versión recomendada | Notas |
|--------------------|--------------------|-------|
| [Node.js](https://nodejs.org/) | LTS (>= 16) | Necesario para gestionar dependencias y scripts. |
| [Rust](https://www.rust-lang.org/) | >= 1.70 | Requerido por Tauri para compilar. |
| [Tauri CLI](https://tauri.app/) | v2.x | Instalar con `npm install -g @tauri-apps/cli` o `npx`. |
| **Windows 10/11**  | - | Optimizado para este sistema. |

---

## Instalación para desarrollo

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/usuario/netport-configurator.git
   cd netport-configurator
