# IPC_Honduras
Series del IPC de Honduras, incluyendo ensayos de pronóstico.

Se ejecuta un proceso en Python, contenido en el archivo "Inflacion_Colab.qmd", mediante el cual se descargan los datos mensuales actualizados de:

- IPC de Honduras, general y por grupos;
- Índices de precios de commodities (FMI);
- Precio internacional del petróleo (WTI);
- Tipo de cambio nominal de Honduras;
- Oferta de dinero en Honduras;

En cada una de estas series se grafica el dato original, la variación interanual y el comportamiento estadístico (histograma) de dicha variación.

Posteriormente, se evalúan seis procedimientos (6) de regresión lineal, usando `scikit-learn` para las primeras cuatro.

1. Mínimos Cuadrados Ordinarios (MCO);

2. Lasso;

3. Regresión Bayesiana (Ridge);

4. Regresión Lineal Generalizada;

5. ARIMA; y

6. MCO sin selección aleatoria de las muestras.

Al final se hace una comparación de los resultados fuera de muestra de estos modelos.
