# Flujo Batch de Monitoreo Hospitalario

## Contenido
- Código y configuración del flujo batch.
- Simulación de dataset hospitalario.
- Visualizaciones y alertas críticas.
- Evidencia de ejecución.

## Introducción y Objetivos
Este notebook simula un flujo batch para monitoreo hospitalario.
Objetivos:
- Detectar casos críticos según estado, días de hospitalización y costo.
- Visualizar alertas y estadísticas por ventanas de pacientes.
- Documentar el flujo y generar evidencia visual y exportable.

## Cómo usar
1. Ejecutar todas las celdas del notebook.
2. Ajustar `chunk_size` y `delay` según necesidad.
3. Revisar alertas, tablas y gráficos generados.

## Criterios de criticidad
- Estado de alta: Fallecido.
- Días de hospitalización > promedio + desviación estándar.
- Costo total > $3.000.000.
