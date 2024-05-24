# Data Governance Analysis

Este repositorio contiene el código en Python utilizado para el análisis automatizado de menciones de principios de gobernanza en documentos PDF. El propósito de este proyecto es identificar y cuantificar la frecuencia con la que se mencionan ciertos principios de gobernanza en una colección de documentos relacionados con la gobernanza de datos textuales digitales.

## Descripción

El script `data_governance_analysis.py` realiza las siguientes tareas:
1. Carga de documentos PDF.
2. Extracción de texto de los documentos.
3. Identificación de menciones de principios de gobernanza utilizando expresiones regulares.
4. Conteo de menciones por documento y de forma global.
5. Generación de tablas resumen con los resultados del análisis.

## Principios Analizados

Los principios de gobernanza analizados en este estudio son:
- Transparencia
- Roles
- Seguridad
- Privacidad
- Accesibilidad
- Calidad
- Políticas
- Madurez
- Ciclo de vida de los datos

## Uso

### Requisitos

Para ejecutar el código, asegúrate de tener instalado Python 3.x y las siguientes bibliotecas:

```bash
pip install PyPDF2 pandas
```
