# Food App: A/B Test Analysis for Interface Optimization 🍔

This project involves analyzing the results of an A/B test for a food product startup. The goal was to determine if changing the font across the entire application influenced user behavior. I conducted a comprehensive analysis of the sales funnel and performed multiple statistical hypothesis tests to ensure the results were significant and not due to chance.

## Key Technical Features
- **Funnel Analysis:** Mapped the user journey from the Main Screen to Payment Confirmation, identifying where the largest drop-offs occurred (nearly 38% after the main screen).
- **Hypothesis Testing:** Conducted **z-tests** for proportions across three groups (two control groups and one test group) to compare conversion rates.
- **Multiple Testing Correction:** Applied the **Bonferroni Correction** to maintain statistical integrity and control the family-wise error rate across 16 simultaneous tests.
- **Data-Driven Conclusion:** Determined that the font change did not significantly affect user behavior, providing a "no-go" recommendation to avoid unnecessary implementation costs.

## Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, SciPy, Plotly, Matplotlib.
- **Statistical Methods:** Z-test for proportions, Bonferroni Correction, Event Funnels.

**[View Project Notebook](https://github.com/carlos-aguirreta/food_app_ab_testing/blob/main/notebook.ipynb)**

<br>
<br>

# Food App: Análisis de Test A/B para Optimización de Interfaz 🍔

Este proyecto consiste en el análisis de los resultados de un test A/B para una startup de productos alimenticios. El objetivo fue determinar si el cambio de fuentes en toda la aplicación influía en el comportamiento de los usuarios. Realicé un análisis exhaustivo del embudo de ventas y múltiples pruebas de hipótesis estadísticas para asegurar que los resultados fueran significativos.

## Características Técnicas Clave
- **Análisis de Embudo (Funnel):** Mapeo del recorrido del usuario desde la pantalla principal hasta la confirmación de pago, identificando que la mayor pérdida de usuarios ocurre tras la pantalla inicial (~38%).
- **Pruebas de Hipótesis:** Ejecución de **pruebas Z** para proporciones entre tres grupos (dos de control y uno experimental) para comparar tasas de conversión.
- **Corrección por Pruebas Múltiples:** Aplicación de la **Corrección de Bonferroni** para mantener la integridad estadística y controlar la tasa de error al realizar 16 pruebas simultáneas.
- **Conclusión Basada en Datos:** Se determinó que el cambio de fuente no afectó significativamente el comportamiento, recomendando no proceder con el cambio para evitar gastos innecesarios.

## Herramientas Utilizadas
- **Lenguaje:** Python
- **Librerías:** Pandas, NumPy, SciPy, Plotly, Matplotlib.
- **Métodos Estadísticos:** Prueba Z para proporciones, Corrección de Bonferroni, Embudos de Eventos.

**[Ver Notebook del Proyecto](https://github.com/carlos-aguirreta/food_app_ab_testing/blob/main/notebook.ipynb)**
