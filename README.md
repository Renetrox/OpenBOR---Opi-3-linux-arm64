# OpenBOR para ARM64 y Orange Pi 3B

Este repositorio contiene una versión modificada de OpenBOR (Open Beats of Rage) compatible con dispositivos ARM64, específicamente optimizada para la Orange Pi 3B.

## Características principales

- **Compatibilidad ARM64**: Modificaciones realizadas para compilar y ejecutar OpenBOR en dispositivos ARM64.
- **Optimización para Orange Pi 3B**: Ajustes específicos para el hardware y sistema operativo de la Orange Pi 3B.
- **Compatibilidad extendida**: Probado en distribuciones basadas en Debian y Ubuntu.

## Requisitos del sistema

- **Dispositivo**: Orange Pi 3B o cualquier dispositivo ARM64.
- **Sistema operativo**: Debian 11/12, Ubuntu 20.04/22.04, o sistemas compatibles.
- **Dependencias**:
  - SDL2
  - GCC/G++
  - Make
  - Git

## Instrucciones de instalación

1. Clona este repositorio:

   ```bash
   git clone https://github.com/tu_usuario/tu_repositorio.git
   cd tu_repositorio
   ```

2. Instala las dependencias necesarias:

   ```bash
   sudo apt update
   sudo apt install -y libsdl2-dev build-essential git
   ```

3. Compila OpenBOR:

   ```bash
   make
   ```

4. Ejecuta OpenBOR:

   ```bash
   ./OpenBOR
   ```

## Notas específicas para Orange Pi 3B

- **Hardware**: Este proyecto aprovecha las capacidades del procesador Rockchip RK3566 y la GPU ARM Mali G52 2EE.
- **Sistema**: Se recomienda utilizar Orange Pi OS (basado en Debian) para una experiencia más optimizada.
- **Configuraciones adicionales**:
  - Ajusta el escalado y la resolución desde el archivo de configuración para un rendimiento óptimo.

## Personalización

Puedes añadir tus propios juegos de OpenBOR en el directorio `Paks`. Simplemente coloca los archivos `.pak` dentro de esta carpeta.

## Créditos

- **OpenBOR**: Proyecto original desarrollado por la comunidad de Beats of Rage.
- **Adaptaciones ARM64**: Implementadas por @Renetrox.
- **Contribuciones**: Agradecimientos a todos los que ayudaron en el desarrollo y pruebas.

## Licencia

Este proyecto utiliza la misma licencia que OpenBOR. Consulta el archivo `LICENSE` para más detalles.

---

¡Disfruta de tus juegos en tu Orange Pi 3B!

