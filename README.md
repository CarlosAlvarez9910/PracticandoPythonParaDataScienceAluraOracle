# Análisis Integral de Desempeño de Tiendas

Este repositorio contiene un **análisis integral de desempeño de cuatro tiendas**, realizado en Google Colab, con el objetivo de determinar cuál tienda sería más conveniente vender o reorganizar para abrir un nuevo negocio.  

El análisis combina múltiples métricas: ventas totales, calificación promedio de clientes, costo de envío promedio, relevancia de las categorías de productos y productos más/menos vendidos, generando un **Score global** para cada tienda.

---

## Contenido del Repositorio

- `Colab_Notebook.ipynb` : Notebook de Google Colab donde se realiza todo el análisis, incluyendo cálculo de métricas, Score global y generación de gráficos.
- `graficos/` : Carpeta que contiene los gráficos generados durante el análisis:
  - `ventas_totales.png` : Total vendido por tienda.
  - `calificacion_promedio.png` : Calificación promedio de clientes.
  - `costo_envio.png` : Costo de envío promedio.
  - `score_global.png` : Score global por tienda.
- `Informe_Final_Tiendas.md` : Informe completo en formato Markdown (opcional, si se guarda desde Colab).

---

## Descripción del Análisis

1. **Variables consideradas**
   - Ventas totales
   - Calificación promedio
   - Costo de envío promedio
   - Contribución de categorías más vendidas

2. **Metodología**
   - Normalización de todas las métricas mediante min-max scaling.
   - Cálculo de un Score global como promedio simple de las métricas normalizadas.

3. **Resultados**
   - Se muestra el Score global de cada tienda.
   - Observaciones detalladas por tienda sobre desempeño, eficiencia y satisfacción del cliente.
   - Gráficos que ilustran los ingresos, calificaciones, costos y Score global.

4. **Conclusión y Recomendación**
   - Tienda 3 y Tienda 2: Mantener por mejor desempeño y balance integral.
   - Tienda 4: Mantener con mejoras.
   - **Tienda 1:** Recomendada para vender o reorganizar debido a su bajo Score global, alta ineficiencia operativa y baja satisfacción del cliente.

---

## Uso

1. Abrir `Colab_Notebook.ipynb` en Google Colab.
2. Ejecutar todas las celdas para generar:
   - DataFrames con métricas.
   - Gráficos de desempeño.
   - Informe Markdown directamente en Colab.
3. Revisar el informe y gráficos para la toma de decisiones estratégicas.

---

## Tecnología

- Python 3
- Pandas
- Matplotlib
- Google Colab

---

## Autor

- **Tu Nombre**  
  Proyecto de análisis de desempeño de tiendas para toma de decisiones estratégicas.
