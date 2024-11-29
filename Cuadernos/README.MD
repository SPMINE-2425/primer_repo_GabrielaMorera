# Carpeta: `cuadernos`

La carpeta `cuadernos` está destinada a almacenar todos los **notebooks de Jupyter** o cuadernos relacionados con el proyecto de ciencia de datos. Estos archivos suelen estar en formato `.ipynb` y se utilizan para documentar y ejecutar código de manera interactiva, combinando explicaciones, visualizaciones y resultados.

## Contenido esperado en esta carpeta

1. **Exploración de datos (EDA):**
   - Cuadernos que contienen análisis exploratorios para entender los datos, identificar patrones, relaciones, anomalías y tendencias.
   - Ejemplo: `eda_inicial.ipynb`, `analisis_distribuciones.ipynb`.

2. **Prototipos de modelos:**
   - Cuadernos donde se prueban y comparan diferentes enfoques de modelado, algoritmos y técnicas.
   - Ejemplo: `modelos_regresion.ipynb`, `clasificacion_baseline.ipynb`.

3. **Visualizaciones:**
   - Cuadernos dedicados a generar gráficos o visualizaciones avanzadas que complementen los análisis.
   - Ejemplo: `graficos_avanzados.ipynb`.

4. **Pruebas y validaciones:**
   - Cuadernos donde se realizan pruebas de hipótesis, validaciones de datos o comprobaciones específicas.
   - Ejemplo: `validacion_modelos.ipynb`.

5. **Documentación de experimentos:**
   - Cuadernos que describen en detalle los experimentos realizados, incluyendo configuraciones, métricas y conclusiones.
   - Ejemplo: `experimento_01.ipynb`.

## Organización sugerida

- **Estructura por temas o fases:**  
  Si el proyecto es grande, se recomienda organizar los cuadernos en subcarpetas según el tema o la etapa del proyecto.  
  Ejemplo:  
  ```
  cuadernos/
  ├── exploracion/
  │   └── eda_inicial.ipynb
  ├── modelos/
  │   └── regresion_logistica.ipynb
  ├── visualizaciones/
  │   └── comparacion_metricas.ipynb
  ```

- **Convención de nombres:**  
  Para facilitar la búsqueda, es importante utilizar nombres claros y descriptivos en los cuadernos. Se recomienda el formato:
  ```
  <tema>_<descripción>.ipynb
  ```
  Ejemplo: `eda_distribuciones_clase.ipynb`, `modelo_random_forest.ipynb`.

## Buenas prácticas

1. **Comentarios y Markdown:**  
   Usa celdas de Markdown para explicar cada paso del análisis, conclusiones, y justificar las decisiones tomadas.

2. **Control de versiones:**  
   Evita almacenar cuadernos con demasiada salida en las celdas (como grandes tablas o gráficos) para facilitar su seguimiento en sistemas de control de versiones como Git.

3. **Referencias a datos:**  
   Si el cuaderno depende de archivos en la carpeta `datos`, utiliza rutas relativas para mantener la portabilidad del proyecto. Ejemplo: `../datos/dataset_principal.csv`.