# 📊 Análisis de Satisfacción Laboral — Power BI

Análisis interactivo de los factores que influyen en la satisfacción laboral
de los empleados, utilizando el dataset HR-Employee-Data (1.471 registros, 27 variables).

---

## 👥 Dashboard Interactivo: People Analytics - Satisfacción Laboral

Este informe analiza el clima organizacional, identificando los principales factores que influyen en la satisfacción e insatisfacción de los empleados dentro de la compañía.

<p align="center">
  <a href="https://app.powerbi.com/view?r=eyJrIjoiNjFhMGNkYTAtMmRiMC00YTU4LWJmYWYtMjdiMGNiMTNiMWRiIiwidCI6IjViMGFiY2EyLWUwYjYtNGYwYS1iODc4LWE3YmM1Mjg4M2NhMCIsImMiOjR9" target="_blank">
    <img src="https://img.shields.io/badge/ACCEDER_AL_DASHBOARD_INTERACTIVO-EA3D2F?style=for-the-badge&logo=microsoftpowerbi&logoColor=white" alt="Ver Dashboard HR" />
  </a>
</p>


---

## 🎯 Objetivo

Identificar qué factores — balance vida-trabajo, horas extra, rendimiento,
participación y clima laboral — tienen mayor impacto en la satisfacción
de los empleados, para orientar decisiones de RRHH basadas en datos.

## 🔍 Hipótesis

La satisfacción laboral está relacionada positivamente con el balance vida-trabajo,
el nivel de participación y un rendimiento más alto. Los empleados que no realizan
horas extra tienden a reportar mayor satisfacción.

**Resultado: hipótesis confirmada por los datos.**

## 📈 Principales hallazgos

- Tasa de rotación anual: **23,74%**
- Solo el **10%** de los empleados tiene un balance vida-trabajo excelente
- El área de **Investigación y Desarrollo** lidera en satisfacción y rendimiento
- Los empleados con **menor antigüedad** reportan mayor satisfacción
- Un clima laboral positivo tiene impacto directo en los extremos de satisfacción

## 🛠️ Herramientas y técnicas

- **Power BI** — modelado, visualización y dashboard interactivo
- **Power Query** — limpieza y transformación de datos
- **DAX** — medidas calculadas (tasa de rotación, promedios por departamento,
  segmentación de satisfacción por niveles)
- **Modelo estrella** — tabla de hechos HR-Employee relacionada con
  11 tablas de dimensiones

## 📁 Estructura del proyecto
```
├── INFORME_SATISFACCION_LABORAL.pdf   # Documentación completa
├── dashboard_satisfaccion.pbix        # Archivo Power BI
└── README.md
```

## 📊 Páginas del dashboard

| Página | Descripción |
|---|---|
| Portada | Navegación general del informe |
| Glosario | Definición de variables clave |
| Global | KPIs generales y satisfacción por área |
| Balance | Impacto del balance vida-trabajo en rendimiento |
| Rendimiento | Relación entre nivel educativo, área y desempeño |
| Indicadores Clave | Métricas ejecutivas y análisis de extremos |

## 👤 Autor

**Tomás Grillanini** — Data Analyst-
