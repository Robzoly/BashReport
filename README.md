# Diagnóstico del Sistema en Linux

## Descripción

`diagnostico.sh` es un script en Bash diseñado para recopilar información esencial del sistema en entornos Linux. Proporciona detalles sobre la configuración de red, conectividad, información del sistema y temperatura del procesador, facilitando tareas de diagnóstico y monitoreo.

## Características

- Obtención de direcciones MAC de las interfaces de red.
- Visualización de la configuración completa de red.
- Prueba de conectividad a localhost.
- Información general del sistema y de la CPU.
- Lectura de la temperatura del procesador (si está disponible).

## Requisitos

- Sistema operativo Linux con Bash instalado.
- Herramientas necesarias: `ip`, `ping`, `uname`, `lscpu`, `bc`.
- Acceso a la terminal con permisos de ejecución.

## Instalación

1. Clona este repositorio o descarga el archivo `diagnostico.sh`.
2. Asigna permisos de ejecución al script:

   ```bash
   chmod +x diagnostico.sh
   ```


## Uso

Ejecuta el script desde la terminal:


```bash
./diagnostico.sh
```


Para guardar la salida en un archivo:


```bash
./diagnostico.sh > salida_diagnostico.txt
```


O para visualizar y guardar simultáneamente:


```bash
./diagnostico.sh | tee salida_diagnostico.txt
```


## Notas

- La lectura de la temperatura del procesador depende del hardware y puede no estar disponible en todos los sistemas.
- Asegúrate de tener instaladas las herramientas requeridas para el correcto funcionamiento del script.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

---
