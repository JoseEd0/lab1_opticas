# Lab 1

Análisis de Movimiento Armónico Simple (MAS) con datos de Vernier.

## Requisitos

- Python 3.8 o superior
- Archivos de datos: `10Hz.txt`, `20Hz.txt`, `30Hz.txt`

## Instalación y Ejecución

### Opción 1: Ejecución Local

1. **Crear entorno virtual:**
   ```bash
   python -m venv venv
   ```

2. **Activar entorno virtual:**
   - macOS/Linux:
     ```bash
     source venv/bin/activate
     ```
   - Windows:
     ```bash
     venv\Scripts\activate
     ```

3. **Instalar dependencias:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Ejecutar el script:**
   ```bash
   python lab1.py
   ```

### Opción 2: Google Colab

1. Abre `lab1.ipynb` en Google Colab
2. Sube los archivos de datos (10Hz.txt, 20Hz.txt, 30Hz.txt) cuando se te solicite
3. Ejecuta todas las celdas

## Descripción

El proyecto realiza:
- Ajuste de curvas con modelo MAS
- Análisis de Transformada de Fourier (FFT)
- Visualización de cinemática y espacio de fase
- Identificación de frecuencias armónicas
