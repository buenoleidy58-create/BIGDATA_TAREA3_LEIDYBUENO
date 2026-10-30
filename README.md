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

## Autora

Leidy Paola Bueno Triana

Universidad Nacional Abierta y a Distancia (UNAD)
Octubre de 2026
