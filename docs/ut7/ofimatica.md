# Aplicaciones ofimáticas y documentación

Las aplicaciones ofimáticas permiten redactar documentación técnica, organizar hojas de cálculo y elaborar presentaciones. Trabajar con plantillas y formatos estándar facilita mantener la coherencia y reproducibilidad de los documentos.

## Herramientas habituales y formatos

| Herramienta | Uso principal | Formatos comunes |
| :--- | :--- | :--- |
| **Procesador de textos** | Memorias técnicas, guías, procedimientos y cartas | `.docx`, `.odt`, `.pdf` |
| **Hoja de cálculo** | Inventarios, presupuestos, tablas de datos y fórmulas | `.xlsx`, `.ods`, `.csv` |
| **Presentaciones** | Exposiciones breves y resúmenes visuales | `.pptx`, `.odp`, `.pdf` |

## Ejemplo de exportación o conversión desde terminal

```bash
# Convertir un documento a PDF sin abrir interfaz gráfica con LibreOffice
libreoffice --headless --convert-to pdf documento_tecnico.docx