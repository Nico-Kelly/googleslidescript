# Google Slides Downloader (View-Only)

[![Language: English](https://img.shields.io/badge/Language-English-blue)](#english) [![Language: Español](https://img.shields.io/badge/Idioma-Español-green)](#español)

[English](#english) | [Español](#español)

---

## English

A simple script whose sole purpose is to download / export **view-only** Google Slides presentations as PDF.

> [!NOTE]
> **Browser Compatibility:** Tested on **Google Chrome**. It is unknown if this works properly on other browsers (Firefox, Safari, Edge, etc.).

### How to Use

1. Open the **Google Slides** presentation you want to download (in view/presentation mode).
2. Press <kbd>F12</kbd> (or right-click anywhere and select **Inspect**) to open Developer Tools.
3. Switch to the **Console** tab.
4. Copy the entire contents of [`downloadslide.js`](downloadslide.js) and paste it into the console.
5. Press <kbd>Enter</kbd>.
6. The script will automatically cycle through all the slides to extract them.
7. Once finished, the print dialog will open automatically. Choose **Save as PDF** as your destination and save your file.

---

## Español

Un script simple cuyo único propósito es descargar / exportar presentaciones de **Google Slides en modo solo lectura** (view-only) en formato PDF.

> [!NOTE]
> **Compatibilidad de Navegadores:** Probado y diseñado para **Google Chrome**. Se desconoce si funciona correctamente en otros navegadores (Firefox, Safari, Edge, etc.).

### Cómo Usar

1. Abre la presentación de **Google Slides** que deseas descargar (en modo visualización/presentación).
2. Presiona <kbd>F12</kbd> (o haz clic derecho en cualquier parte y selecciona **Inspeccionar**) para abrir las herramientas de desarrollador.
3. Ve a la pestaña **Consola** (**Console**).
4. Copia todo el contenido de [`downloadslide.js`](downloadslide.js) y pégalo en la consola.
5. Presiona <kbd>Enter</kbd>.
6. El script avanzará automáticamente por todas las diapositivas para capturarlas.
7. Al finalizar, se abrirá automáticamente el cuadro de diálogo de impresión. Selecciona **Guardar como PDF** como destino y guarda el archivo.

