# Proyecto: Análisis de Viajes Compartidos en Zuber

## Contexto
En este proyecto, el analista trabaja para **Zuber**, una nueva empresa de viajes compartidos en Chicago. El objetivo principal es entender los patrones en los viajes a través de un análisis de los datos de los usuarios y probar la hipótesis de que las condiciones climáticas afectan la duración de los viajes, especialmente los sábados.

## Herramientas Utilizadas
- **Python:** para el procesamiento de datos y pruebas estadísticas.
- **Pandas:** para manipulación y análisis de datos.
- **Matplotlib / Seaborn:** para la visualización de los resultados en gráficos.
- **SciPy:** para realizar pruebas estadísticas como t-test y análisis de hipótesis.
- **SQL (si aplica):** para consultas relacionadas con la base de datos.

## Análisis de Resultados
### 1. **Análisis Exploratorio**
- Se identificaron patrones en los **tipos de viajes** y las zonas más solicitadas. La relación entre el clima y la cantidad de viajes es clara, ya que los viajes disminuyen en condiciones de clima adverso.
- **Visualización de Barrios:** Se visualizó el número de finalizaciones de viaje por barrio, mostrando que las zonas más céntricas y turísticas tienen mayor actividad.
- **Empresas de Taxis:** Se comparó el número de viajes entre Zuber y sus competidores para identificar la cuota de mercado y las preferencias de los pasajeros.

### 2. **Prueba de Hipótesis**
- Se formuló una hipótesis para comprobar si la duración de los viajes desde el Loop hasta el Aeropuerto O'Hare cambia los sábados lluviosos.
- El análisis utilizando un **t-test** mostró que, efectivamente, los sábados lluviosos tienen un **efecto significativo** en la duración de los viajes, lo que valida la hipótesis alternativa.

## Conclusiones
- **Impacto del Clima:** El clima afecta la duración de los viajes, especialmente los sábados lluviosos, lo cual es un hallazgo crucial para la empresa para optimizar las operaciones durante estos días.
- **Preferencias de los Pasajeros:** Las zonas cercanas al Loop tienen más viajes finales, lo que indica una alta demanda en estas áreas.
- **Recomendaciones:** Zuber podría adaptar sus estrategias de precios y promociones, tomando en cuenta el clima y las zonas con más demanda. Además, podrían mejorar la predicción de tiempos de viaje para los sábados lluviosos, ofreciendo incentivos para los pasajeros.

Este proyecto proporciona una visión más clara de cómo el clima y las zonas geográficas impactan en la demanda y duración de los viajes compartidos, lo que permitirá a Zuber tomar decisiones más informadas para optimizar sus operaciones.
