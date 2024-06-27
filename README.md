# Proyecto Integrado: Optimización de Gastos de Marketing para Y.Afisha

## Descripción del Proyecto

En este proyecto, trabajamos con Y.Afisha para optimizar los gastos de marketing. Utilizamos datos de visitas al sitio web, pedidos y gastos de marketing para analizar cómo los clientes usan el servicio, cuándo empiezan a comprar, cuánto dinero aportan a la compañía y cuándo los ingresos cubren el costo de adquisición de los clientes.

## Objetivos del Proyecto

- Analizar cómo los clientes usan el servicio.
- Determinar cuándo los clientes comienzan a comprar.
- Calcular el valor aportado por cada cliente (LTV).
- Evaluar cuándo los ingresos cubren el costo de adquisición de los clientes (CAC).
- Optimizar las inversiones en marketing y calcular el Retorno sobre la Inversión en Marketing (ROMI).

## Pasos Realizados en el Proyecto

### Paso 1: Descarga y Preparación de los Datos

- **Archivos de Datos:**
  - `/datasets/visits_log_us.csv`: Datos de visitas.
  - `/datasets/orders_log_us.csv`: Datos de pedidos.
  - `/datasets/costs_us.csv`: Datos de gastos de marketing.

- **Preparación de Datos:**
  - Cargamos los datos en DataFrames de pandas.
  - Revisamos y optimizamos los tipos de datos.
  - Renombramos columnas para facilitar su uso.
  - Calculamos las sesiones diarias, semanales y mensuales.
  - Calculamos la duración de cada sesión.
  - Analizamos la frecuencia de retorno de los usuarios.

### Paso 2: Informes y Cálculo de Métricas

#### Visitas:
- **Métricas Calculadas:**
  - Número de usuarios diarios, semanales y mensuales.
  - Número de sesiones por día.
  - Duración promedio de cada sesión.
  - Frecuencia de retorno de los usuarios.

#### Ventas:
- **Métricas Calculadas:**
  - Tiempo desde el registro hasta la primera compra (conversión).
  - Número de pedidos por período de tiempo.
  - Tamaño promedio de compra.
  - Lifetime Value (LTV) de los clientes.

#### Marketing:
- **Métricas Calculadas:**
  - Gastos totales y por fuente de adquisición a lo largo del tiempo.
  - Costo de Adquisición de Clientes (CAC) por fuente.
  - Rentabilidad de las inversiones en marketing (ROMI).

### Paso 3: Análisis de Datos

- Identificamos los 10 principales barrios en términos de finalización del recorrido.
- Generamos gráficos para visualizar:
  - Empresas de taxis y número de viajes.
  - Los 10 barrios principales por número de finalizaciones.
- Analizamos y explicamos los resultados de los gráficos.

### Paso 4: Prueba de Hipótesis

- **Hipótesis:**
  - "La duración promedio de los viajes desde el Loop hasta el Aeropuerto Internacional O'Hare cambia los sábados lluviosos."
- **Proceso:**
  - Formulación de la hipótesis nula y alternativa.
  - Selección del nivel de significación (alfa).
  - Uso del criterio adecuado para probar las hipótesis.
  - Análisis de los resultados.

### Resultados y Conclusión

- **CAC y ROMI por Fuente:**
  - Identificamos las fuentes de adquisición más eficientes.
  - Recomendamos reevaluar las fuentes con bajo ROMI.

- **Conclusiones:**
  - **Estrategia de Adquisición Eficiente:** Las fuentes 1 y 2 muestran la mayor eficiencia en términos de CAC y ROMI.
  - **Reevaluación de Estrategias:** Las fuentes 3 y 10 requieren una revisión crítica.
  - **Inversión Estratégica y Rentabilidad:** La inversión debe centrarse en las fuentes más rentables y mejorar las estrategias de las fuentes de menor rendimiento.

## Conclusión General

El análisis muestra que la eficiencia en la adquisición y retención de clientes, junto con una comprensión del comportamiento de compra, son claves para optimizar los gastos de marketing y mejorar el retorno de la inversión para Y.Afisha.

## Contribución

Si deseas contribuir a este proyecto, realiza un fork del repositorio y crea una pull request con tus mejoras. Asegúrate de que tu código sigue los lineamientos del proyecto y está bien comentado.

## Licencia

Este proyecto está bajo la licencia MIT. Para más detalles, consulta el archivo LICENSE.
