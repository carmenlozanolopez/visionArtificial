# Sistema de Detección de Dorsales en Carreras

## Descripción del Proyecto
El propósito de este proyecto es desarrollar un sistema para la detección de dorsales en fotografías tomadas durante carreras. Actualmente, muchas competiciones publican imágenes de forma pública, permitiendo que cualquiera pueda acceder a ellas. Este sistema pretende limitar el acceso a las imágenes, de forma que los usuarios puedan acceder únicamente a las fotos en las que aparecen ellos mismos.

## Diferentes Aplicaciones
Este sistema se puede aplicar en otros casos parecidos como:
- **Reconocimiento de matrículas**
- **Gestión de eventos**: Identificando los asistentes a través de credenciales con números
- **Automatización de procesos industriales**: Identificando productos o componentes con números de serie

## Tecnologías Utilizadas
- **Lenguajes de programación**: 
  - Python
  - Jupyter Notebook
- **Bibliotecas**: 
  - PIL
  - cv2
  - ultralytics
- **Herramientas**: 
  - YOLO
  - OCR

## Instrucciones de Instalación
1. Ejecuta el archivo `trabajo_4` en el entorno correspondiente.
2. En principio, el sistema está configurado para funcionar sin problemas. En caso de encontrar errores, verifica las direcciones de las carpetas y ajusta según sea necesario.

## Uso
1. Carga las imágenes de la carrera en la carpeta correspondiente.
2. Ejecuta el script para procesar las imágenes y detectar los dorsales.
3. Los resultados se almacenarán en una carpeta designada, con acceso controlado según los dorsales detectados.
