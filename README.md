# EvaluacionU1_YanezGustavo
# Flujo Reproducible U1: Análisis Experimental vs. Teórico de Deflexión en Vigas

Este repositorio contiene la resolución de la **Evaluación 1 (Unidad 1)** de la asignatura *Herramientas Computacionales para Ingeniería II* (Departamento de Ingeniería en Obras Civiles, USACH).

## 1. Problema

El objetivo general es analizar la deflexión en el centro de la luz de una viga de acero simplemente apoyada bajo una carga puntual central. Se busca verificar el grado de ajuste entre los datos medidos experimentalmente en laboratorio y el modelo teórico de flexión elástica de Euler-Bernoulli, evaluando la rigidez equivalente y las diferencias relativas dentro del rango elástico.

---

## 2. Archivos: Entrada, Proceso y Salida

El repositorio sigue la siguiente arquitectura de carpetas y archivos relativas:

```text
mi-repositorio/
├── README.md                  # Manual e instrucciones de reproducibilidad
├── USO_IA.md                  # Registro y auditoría de uso de IA
├── data/                      # DATOS ORIGINALES (No modificar ni sobrescribir)
│   │── datos_viga.csv         # Mediciones de carga y deflexión
│   │── parametros_viga.xlsx   # Propiedades geométricas y mecánicas
├── analysis/
│   └── analisis_viga.py       # Script de Python para procesamiento y gráficos
├── figures/
│   └── carga_deflexion.png    # Gráfico de resultados (Salida)
└── report/
    ├── main.tex               # Código fuente principal de la nota técnica en LaTeX
    ├── referencias.bib        # Archivo BibTeX con la bibliografía (Hibbeler)
    └── nota_tecnica.pdf       # Documento final compilado (Salida)
