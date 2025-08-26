# Laboratorio: Codificación de la Fuente con Raspberry Pi Pico

Este repositorio contiene el desarrollo de la Guía de Laboratorio de Comunicaciones Digitales, enfocada en la exploración de conceptos de conversión A/D (analógica-digital) utilizando la placa Raspberry Pi Pico 2W.

#Objetivo

Comprender los conceptos de conversión A/D y su aplicación en la arquitectura de un sistema de comunicación digital, mediante el uso de Python/MicroPython, MATLAB y el análisis de datos muestreados.

# Parte A — Uso del conversor A/D

Configuración de entradas del ADC en la Raspberry Pi Pico.

Lectura de valores analógicos con la función read_u16().

Conversión de valores de 16 bits a 12 bits reales.

Visualización de señales en el Plotter de Thonny.

# Parte B — Muestreo de señales

Ejecución del programa adc.m en MATLAB para analizar tasa de muestreo y número de muestras por periodo.

Implementación de ADC_Sampling.py en la Raspberry Pi Pico.

Generación de archivos .CSV con datos de muestreo.

Procesamiento y comparación de la señal original vs. reconstrucción a partir de muestras.

# Parte C — Análisis estadístico

Muestreo de señales DC con diferentes valores de entrada (0 a 3.2V).

Uso del programa sampling_2.py para calcular media y desviación estándar.

Procesamiento en Python/MATLAB para validar resultados.

Visualización de histogramas y análisis de ruido en la conversión.
