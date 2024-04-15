# ChatGPT Webview

Este proyecto consiste en un webview de la página oficial de ChatGPT utilizando Tauri y Rust.

## Propósito

El propósito principal de este proyecto es proporcionar un acceso rápido y eficiente a la página oficial de ChatGPT. Utilizando Tauri y Rust, se busca acelerar la carga de la página y reducir el consumo de memoria en comparación con otros enfoques.

## Características

- Acceso rápido a la página oficial de ChatGPT.
- Utiliza Tauri para crear una aplicación de escritorio multiplataforma.
- Implementado en Rust para un rendimiento optimizado y una menor huella de memoria.

## Requisitos

- Rust
- Node.js
- Tauri CLI
- bun

## Instalación

1. Clona este repositorio:

```bash
git clone https://github.com/thexmep/chatgtp-unnoficial-webview.git
```

2. Navega hasta el directorio del repositorio clonado:
```bash
cd chatgtp-unnoficial-webview
```

3. Instala las dependencias de Node.js:
```bash
bun install
```

## Ejecucion
Para ejecutar la aplicación en modo de desarrollo, utiliza el siguiente comando:
```bash
bun run tauri dev
```
Esto iniciará la aplicación en tu entorno local.

## Generación de archivos

Si deseas generar los archivos para distribuir la aplicación, puedes utilizar el siguiente comando:
```bash
bun run tauri build
```

Esto creará los archivos necesarios para distribuir la aplicación en los directorios correspondientes según la plataforma.
Directorio : src-tauri/target/release/





