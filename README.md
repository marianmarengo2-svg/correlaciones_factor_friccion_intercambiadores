# Correlaciones de Factor de Fricción en Intercambiadores

Este repositorio es una investigación exhaustiva y un compendio de cálculo sobre los factores de fricción ($f$) aplicados al diseño térmico de intercambiadores de calor de tubo y carcasa.
El objetivo es centralizar desde los métodos clásicos manuales hasta las correlaciones modernas optimizadas para simulación.

## Contenido del Proyecto1. 
### Lado de los Tubos (Flujo Interno)
* Documentación y funciones para el cálculo de $f$ en conductos cerrados:
* Régimen Laminar: Ecuación de Poiseuille ($Re < 2100$).
* Régimen Turbulento:Ecuaciones explícitas: Blasius, Haaland, Swamee-Jain.
* Ecuación implícita: Colebrook-White (Resuelta mediante métodos numéricos).
* Régimen de Transición: Correlación de Churchill, ideal para modelos continuos.
### Lado de la Carcasa (Lado Coraza) 
* Análisis de pérdida de carga basado en la geometría del haz de tubos:
* Método de Kern: El estándar para estimaciones rápidas de $\Delta P_s$.
* Método de Bell-Delaware: Análisis detallado mediante factores de corrección por fugas y bypass.
## Herramientas Utilizadas
* Google Colab: Para la investigación interactiva y validación de fórmulas.
* Python (NumPy/SciPy): Para la resolución de ecuaciones implícitas y automatización.
* LaTeX: Para la representación matemática profesional de las correlaciones.
  
*Este proyecto forma parte de mi portafolio en Ingeniería de Procesos y Ciencia de Datos*
