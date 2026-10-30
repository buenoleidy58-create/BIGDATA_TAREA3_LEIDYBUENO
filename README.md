# BIGDATA_TAREA3_LEIDYBUENO
Proyecto de análisis de datos de movilidad urbana mediante Apache Spark y Kafka, utilizando procesamiento Batch y Streaming.
# Análisis de datos de movilidad urbana mediante Apache Spark y Kafka

## Descripción del proyecto

Este proyecto busca analizar grandes volúmenes de datos relacionados con los viajes en taxi de Nueva York, utilizando herramientas de Big Data como Apache Spark y Apache Kafka.

## Objetivo general

Implementar una solución de procesamiento de datos mediante Apache Spark y Kafka para analizar registros históricos y eventos simulados de viajes, identificando patrones de movilidad y tarifas.

## Conjunto de datos

- Fuente: NYC Taxi and Limousine Commission (TLC).
- Archivo propuesto: yellow_tripdata_2025-01.parquet.
- Formato: Parquet.
- Variables: fecha y hora de recogida, distancia del viaje y tarifa.

## Tecnologías utilizadas

- Python
- Apache Spark
- PySpark
- Apache Kafka
- Spark Structured Streaming

## Procesamiento Batch

Se realizará la carga, limpieza y transformación de los datos históricos para obtener estadísticas sobre los viajes, distancias y tarifas.

## Procesamiento en tiempo real

Se simulará la llegada de nuevos viajes mediante Kafka, utilizando un topic llamado `viajes`. Posteriormente, Spark Structured Streaming procesará los eventos recibidos.

## Resultados

En esta sección se documentarán los resultados obtenidos después de ejecutar los programas.
# Evidencias del proyecto

En esta sección se encuentran los recursos audiovisuales y la presentación correspondientes al proyecto **Análisis de datos de movilidad urbana mediante Apache Spark y Kafka**.
# Resultados del análisis de movilidad urbana

En esta sección se presentan los resultados obtenidos mediante el procesamiento de datos con Apache Spark y Kafka.

## 1. Resultados del procesamiento Batch

El procesamiento Batch permite analizar los registros históricos de viajes en taxi de Nueva York mediante PySpark.

Se evaluarán los siguientes indicadores:

- Número total de registros originales.
- Número de registros válidos después de la limpieza.
- Cantidad de registros descartados.
- Distancia promedio de los viajes.
- Tarifa promedio.
- Hora con mayor cantidad de viajes.

## 2. Resultados del procesamiento en tiempo real

Mediante Apache Kafka y Spark Structured Streaming se procesarán eventos simulados de nuevos viajes.

Se analizarán:

- Cantidad de eventos recibidos.
- Cantidad de eventos procesados correctamente.
- Eventos descartados por contener datos inválidos.
- Estadísticas de los viajes recibidos en las ventanas de tiempo.

## 3. Tablas y gráficas

Se incluirán las tablas y representaciones gráficas generadas durante el análisis, con el propósito de facilitar la interpretación de los patrones de movilidad urbana.

## 4. Análisis de resultados

Los resultados permitirán identificar comportamientos relacionados con la frecuencia de los viajes, las distancias recorridas y las tarifas, tanto en los registros históricos como en los eventos simulados.

**Nota:** Los valores numéricos y las gráficas se incorporarán después de ejecutar y verificar los programas.
## 1. Video de la exposición

[Ver video de la presentación en YouTube](https://youtu.be/D40oex45VpI)

## 2. Presentación del proyecto

[Consultar presentación en Canva](https://canva.link/2pjl02ws261wxz2)

## 3. Evidencias de ejecución

En esta sección se agregarán capturas de pantalla que demuestren la ejecución del procesamiento Batch con PySpark y el procesamiento en tiempo real con Kafka.

## Autora

Leidy Paola Bueno Triana

Universidad Nacional Abierta y a Distancia (UNAD)
Octubre de 2026
