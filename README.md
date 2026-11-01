\# Laboratorio de simulación estocástica



Notebooks de métodos de simulación: generadores de números pseudoaleatorios, pruebas de aleatoriedad, muestreo de variables aleatorias, integración Monte Carlo y aplicaciones (inventario y colas).



No es un producto de predicción. Es la base metodológica detrás de los modelos Monte Carlo del resto del portafolio.



\## Empieza aquí



| Notebook | Qué resuelve |

|---|---|

| \[app-inventario-tinas-tibasa-capacidad-camion.ipynb](app-inventario-tinas-tibasa-capacidad-camion.ipynb) | Caso TIBASA: 5 tinas \~ triangular, probabilidad de exceder 1 t y decisión de camión nuevo vs. flete de emergencia. |

| \[app-colas-dos-estaciones-en-serie.ipynb](app-colas-dos-estaciones-en-serie.ipynb) | Colas en serie: Poisson + exponencial + uniforme. Tiempo medio en sistema y qué cola es más larga. |

| \[app-colas-almacen-camiones-equipo-descarga.ipynb](app-colas-almacen-camiones-equipo-descarga.ipynb) | Ej. 5.6 (Simulación: un enfoque práctico). Almacén 23:00–07:00, distribuciones empíricas, equipos de 3–6 personas. |

| \[mc-integracion-media-muestral-y-acierto-error.ipynb](mc-integracion-media-muestral-y-acierto-error.ipynb) | Integración Monte Carlo: media muestral, acierto-error, varianza e intervalo de confianza. |



\## Contenido



\### Generadores PRNG

\- `prng-cuadrado-medio.ipynb` — método del cuadrado medio

\- `prng-producto-medio.ipynb` — método del producto medio

\- `prng-lcg-basico.ipynb` — generador congruencial lineal

\- `prng-lcg-y-prueba-chi2.ipynb` — LCG + prueba χ²

\- `prng-lcg-tabla-borrador.ipynb`, `prng-lcg-tabulate-ensayo.ipynb` — variantes del LCG



\### Pruebas de aleatoriedad

\- `test-chi2-uniformidad.ipynb`

\- `test-kolmogorov-smirnov.ipynb`

\- `test-corridas-runs.ipynb`



\### Muestreo de variables aleatorias

\- `va-transformada-inversa-triangular.ipynb`

\- `va-aceptacion-rechazo-teoria.ipynb` / `va-aceptacion-rechazo-beta24.ipynb`

\- `va-composicion-triangular.ipynb`

\- `va-exponencial-transformada-inversa.ipynb`

\- `catalogo-generadores-y-ajuste-distribuciones.ipynb` — compilación de generadores y ajuste con fitter



\### Monte Carlo

\- `mc-estimacion-pi-hit-or-miss.ipynb` — π por dardos + Chebyshev

\- `mc-estimacion-probabilidad-convergencia.ipynb`

\- `mc-integracion-media-muestral-y-acierto-error.ipynb`



\### Aplicaciones

\- `app-inventario-tinas-tibasa-capacidad-camion.ipynb`

\- `app-colas-dos-estaciones-en-serie.ipynb`

\- `app-colas-almacen-camiones-equipo-descarga.ipynb`



\### Fuera del hilo de simulación estocástica

\- `nlp-scraping-sentiment-laptops-mercadolibre.ipynb`

\- `edp-esquema-leapfrog-adveccion.ipynb`

\- `edp-leapfrog-y-lax-friedrichs-ensayo.ipynb`

\- `intro-python-listas.ipynb`



\## Stack

Python · NumPy · pandas · matplotlib · SciPy · Jupyter

