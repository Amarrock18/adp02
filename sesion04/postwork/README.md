[`Análisis de Datos con Python`](../../README.md) > [`Sesión 4`](../README.md) > `Postwork`

## Postwork 4

### 1. Objetivos :dart:

- Conocer acerca del análisis exploratorio de datos

### 2. Requisitos :clipboard:

1. Ambiente de conda para el curso levantado
1. Servidor de __Jupyter__ levantado

### 3. Desarrollo :rocket:

Como hemos visto, el análisis exploratorio de datos te servirá para tener una noción clara de cómo se comportan tus datos, y qué es lo que puedes esperar de ellos. Por ejemplo: si tus datos presentan una distribución gaussiana o normal, es posible que cuando vayamos a entrenar un algoritmo de aprendizaje automático, los datos que son menos probables de aparecer sean más difíciles de reconocer.

**Tips:**

Si tu base de datos está muy desbalanceada, lo primero y más recomendable será buscar más datos de aquellas clases que casi no tienes muestras. (por ejemplo: en el caso de ciclistas, quizás convenga buscar ciclistas de edades avanzadas, que aunque hay pocos, es importante contemplarlos).

Si tu base de datos es difícil de nutrir con nuevos datos, puedes intentar retirar aquellos casos muy atípicos, dado que la probabilidad es que casi no aparezcan.

Si tu base de datos realmente presenta demasiado desbalance, puedes intentar con una técnica llamada *Data Augmentation*, el cual, si bien es cierto es muy enfocado a imágenes, te puede dar una idea de cómo hacer crecer tu base de datos artificialmente: http://cs231n.stanford.edu/reports/2017/pdfs/300.pdf


[`Anterior`](../README.md#3-postwork-memo) | [`Siguiente`](../README.md#3-postwork-memo)
