# PCB_Enfasis_III
# Smart Derm Mirror - PCB & 3D Enclosure

Este repositorio contiene los archivos de diseño de hardware y el modelo 3D de la carcasa para el prototipo del Smart Derm Mirror. El esquemático y el diseño de la placa de circuito impreso (PCB) han sido desarrollados utilizando EasyEDA Pro.

## 🛠️ Especificaciones del Sistema
* **Microcontrolador:** ESP32-S3 WROOM 1 N16R8.
* **Procesamiento de Audio:** Amplificador MAX98357A y micrófono INMP441.
* **Interfaz Visual:** Módulo de pantalla E-paper de 2.9 pulgadas (WeAct Studio).
* **Conectividad:** Interfaz USB-C y switch TS3USB221.
* **Carcasa (Enclosure):** Diseño optimizado para impresión 3D, alojando la PCB, la pantalla e-paper y los periféricos de audio.

## 📂 Estructura del Repositorio
* `/Hardware`: Archivo del proyecto de la placa empaquetado (`.epro2`) exportado desde EasyEDA.
* `/3D_Casing`: Archivos de la carcasa 3D (`.STL` para impresión directa y `.STEP` para modificaciones CAD).
* `/Fabrication`: Archivos de producción de la PCB (Gerbers, BOM, CPL).


## 🚀 Cómo visualizar el proyecto
**Para la PCB:**
1. Abre [EasyEDA Pro](https://pro.easyeda.com/).
2. Dirígete a `File` > `Import` > `EasyEDA Professional`.
3. Selecciona el archivo `.epro2` ubicado en la carpeta `/Hardware`.

**Para la Carcasa 3D:**
* Los archivos `.STL` pueden abrirse en cualquier laminador (slicer) como Ultimaker Cura o PrusaSlicer para su impresión.
* Los archivos `.STEP` pueden importarse en software CAD como Fusion 360 o SolidWorks.

## 📋 Estado del Proyecto (Sprint Actual)
* [x] Diseño del esquemático y PCB en EasyEDA.
* [x] Modelado 3D de la carcasa del prototipo.
* [ ] Impresión 3D de la carcasa (pruebas de tolerancia).
* [ ] Generación de archivos de manufactura de la PCB (Gerber/BOM).

## 👥 Equipo
* Laura Valentina Escobar B. - Desarrollador (Hardware/Software)
