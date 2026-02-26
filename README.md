
El análisis completo se encuentra en el archivo `Telecom_x.ipynb`, donde se desarrollan las siguientes etapas:

1. Carga y exploración inicial de datos  
2. Limpieza y tratamiento de datos  
3. Transformación de variables  
4. Análisis exploratorio (EDA)  
5. Visualizaciones  
6. Conclusiones y recomendaciones  

---

## Tecnologías utilizadas

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook

---

## Metodología

El proyecto se desarrolló siguiendo las siguientes fases:

### 1. Exploración inicial
Se realizó una revisión general del dataset para comprender su estructura, tipos de variables y posibles inconsistencias.

### 2. Limpieza de datos
- Conversión de tipos de datos.
- Tratamiento de valores nulos.
- Eliminación de registros inconsistentes.
- Estandarización de variables categóricas.

### 3. Transformación
- Codificación de variables categóricas.
- Creación de variable objetivo binaria.
- Preparación del dataset para análisis.

### 4. Análisis exploratorio
Se analizaron variables categóricas y numéricas para identificar patrones relacionados con el churn.

---

## Principales hallazgos

- El tipo de contrato influye significativamente en la evasión: los contratos mensuales presentan mayor tasa de abandono.
- La antigüedad del cliente (tenure) es un factor determinante: clientes nuevos muestran mayor probabilidad de churn.
- Los cargos mensuales elevados se asocian con mayor tasa de cancelación.
- Los contratos a largo plazo muestran mayor estabilidad y fidelización.

Estos hallazgos permiten identificar segmentos de riesgo y orientar estrategias de retención.

---

## Recomendaciones estratégicas

- Incentivar contratos a largo plazo mediante beneficios o descuentos.
- Implementar estrategias de seguimiento durante los primeros meses del cliente.
- Revisar planes con cargos elevados para ofrecer alternativas más competitivas.
- Diseñar programas de fidelización para clientes con mayor permanencia.

---

## Instalación y dependencias

Si deseas ejecutar el proyecto en un entorno local, instala las siguientes librerías:

```bash
pip install pandas numpy matplotlib seaborn
