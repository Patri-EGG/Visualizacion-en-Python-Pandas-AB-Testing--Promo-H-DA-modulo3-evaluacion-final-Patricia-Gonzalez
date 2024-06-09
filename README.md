# Promo-H-DA-modulo3-evaluacion-final-Patricia-Gonzalez
Evaluación final de módulos 3 Data Analisys.

# Análisis de Datos de Clientes de Aerolíneas

## Introducción
Este repositorio contiene un Jupyter Notebook que realiza un análisis exhaustivo de los datos de clientes de aerolíneas, desde la carga y limpieza de los datos hasta análisis estadísticos avanzados, incluyendo visualizaciones detalladas y pruebas estadísticas para evaluar diferencias en comportamientos de reserva basados en el nivel educativo.

## Estructura del Proyecto
- `Customer Flight Activity.csv`: Datos de actividad de vuelos de clientes.
- `Customer Loyalty History.csv`: Datos históricos de lealtad de los clientes.
- `Analisis-de-Datos-de-Clientes-de-Aerolíneas-Patricia-Gonzalez.ipynb`: Notebook de Jupyter que contiene todo el análisis.
- `ejercicio_final_modulo_3.pdf`: Guía con todos los ejercicios.
- `Flight Activity and Customer Loyalty-CLEAN.csv`: Archivo creado durante el análisis que contiene el DataFrame final limpio.

## Fases del Análisis
### Fase 1: Exploración y Limpieza
- Carga de los conjuntos de datos.
- Combinación de datos usando 'Loyalty Number' como clave.
- Limpieza de datos incluyendo la eliminación de duplicados y la corrección de valores negativos en `Salary`.

### Fase 2: Visualización de Datos
- Visualizaciones que muestran la distribución de vuelos reservados por mes, la relación entre la distancia de los vuelos y los puntos acumulados, y comparaciones del salario promedio entre diferentes niveles educativos.

### Fase 3: Evaluación de Diferencias en Reservas de Vuelos por Nivel Educativo
- Preparación de datos relevantes.
- Análisis descriptivo agrupando los datos por nivel educativo.
- Prueba ANOVA para determinar diferencias significativas entre los niveles educativos.

## Resultados Principales
La prueba ANOVA realizada indica que no hay diferencias estadísticamente significativas en el número de vuelos reservados entre los diferentes niveles educativos, con un p-valor de 0.3161.

## Conclusiones
Los resultados sugieren que el nivel educativo no influye significativamente en la cantidad de vuelos reservados por los clientes. Esto indica que las estrategias de marketing y desarrollo de servicios no deberían basarse únicamente en el nivel educativo para predecir o influir en los comportamientos de reserva de vuelos.

## Cómo Usar este Repositorio
1. Clonar el repositorio.
2. Asegurarse de que Python y los paquetes necesarios están instalados.
3. Ejecutar el notebook `Analisis-de-Datos-de-Clientes-de-Aerolíneas-Patricia-Gonzalez.ipynb` para ver el análisis paso a paso.

## Tecnologías Utilizadas
- Python 3.11.8
- Pandas para manipulación de datos.
- Matplotlib y Seaborn para visualizaciones.
- SciPy para análisis estadísticos.