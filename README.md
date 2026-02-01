Extracción, Análisis y Conversión de Facturas Electrónicas (PDF / XML)
 Descripción del proyecto

Este proyecto implementa un flujo completo para el procesamiento de facturas electrónicas, enfocado principalmente en el contexto peruano (SUNAT), que incluye:

🔍 Detección de XML embebidos en archivos PDF

📎 Extracción y almacenamiento de XML adjuntos

🧠 Análisis de contenido mediante regex sobre texto plano

🔄 Conversión de XML → PDF usando ReportLab

🛡️ Manejo de errores comunes (XML sin nodos, PDFs sin adjuntos, namespaces, etc.)

El objetivo es demostrar un enfoque práctico y robusto para tratar documentos electrónicos reales.

🧰 Tecnologías utilizadas

Python 3.x

PyMuPDF (fitz) → lectura de PDFs y archivos embebidos

xml.etree.ElementTree → parseo de XML

ReportLab → generación de PDFs

re (regex) → extracción de datos desde texto
