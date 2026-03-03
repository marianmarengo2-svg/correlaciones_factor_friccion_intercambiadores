# Optimización de Intercambiadores de Calor: Implementación del Método de Kern en Python

Este repositorio contiene un análisis exhaustivo sobre el cálculo de factores de fricción y la optimización de intercambiadores de calor de carcasa y tubos. 

El proyecto transita desde las correlaciones clásicas de mecánica de fluidos (Moody, Churchill) hasta la simulación paramétrica de rendimiento térmico-hidráulico.

## Alcance del Proyecto

* **Modelado de Tuberías:** Cálculo de factores de fricción para diferentes regímenes de flujo y rugosidades.
* **Simulación de Carcasa (Shell Side):** Implementación de la metodología de Kern para determinar el Diámetro Equivalente ($D_e$) y la Velocidad de Masa ($G_s$).
* **Análisis de Sensibilidad:** Evaluación dinámica de cómo el espaciado de bafles afecta el coeficiente de transferencia de calor ($h_s$) y la caída de presión ($\Delta P_s$).
* **Optimización de Arreglos:** Comparativa de rendimiento entre arreglos de tubos triangulares (30°) y cuadrados (90°).

## Visualización de Resultados

El notebook incluye herramientas de visualización que permiten identificar el punto óptimo de diseño, donde se maximiza la eficiencia térmica sin exceder los límites operativos de presión.

### 1. Diagrama de Moody desde la ecuación de Churchill
Esta gráfica representa la transición del factor de fricción en función del número de Reynolds y la rugosidad relativa, validando el modelo matemático antes de aplicarlo a la carcasa.

![Diagrama de Moody](img/diagrama_moody_churchill.png)

### 2. Comparativa de Arreglos: Triangular vs. Cuadrado
En esta visualización se analiza el compromiso (*trade-off*) entre el coeficiente de transferencia de calor y la pérdida de carga para ambos arreglos geométricos.

![Comparativa de Arreglos](img/sensibilidad_arreglo_coeficientes_kern.png)

## Tecnologías Utilizadas
* **Python:** Core del procesamiento y cálculos.
* **NumPy:** Manejo de vectores para simulaciones paramétricas.
* **Matplotlib:** Generación de gráficos de sensibilidad de doble eje.

---

## 👤 Información de Contacto
**Mariana L. Marengo** *Estudiante avanzada de Ingeniería Química / Trayectoria en Industria* **Enfoque:** Optimización de procesos industriales y modelado térmico-hidráulico mediante Python.

* **GitHub:** [marianmarengo2-svg](https://github.com/marianmarengo2-svg)
* **LinkedIn:** [Mariana Lourdes Marengo](https://www.linkedin.com/in/mariana-lourdes-marengo-790b91148/)
* **Correo:** mmaren2024@gmail.com
