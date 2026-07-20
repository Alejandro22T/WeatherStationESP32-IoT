# Estación Meteorológica IoT

## Descripción

Este proyecto implementa una estación meteorológica basada en Internet de las Cosas (IoT) utilizando una placa ESP32 NodeMCU-32S, un sensor DHT11 y Arduino IoT Cloud.

La solución permite monitorear en tiempo real la temperatura y la humedad desde cualquier lugar mediante un Dashboard en la nube.

---

## Hardware utilizado

- ESP32 NodeMCU-32S
- Sensor DHT11
- Protoboard
- Cable USB

---

## Software utilizado

- Arduino IoT Cloud
- Arduino Cloud Web Editor
- Arduino IoT Cloud Library

---

## Variables Cloud

| Variable | Tipo |
|-----------|------|
| temperature | float |
| humidity | float |
| measurementTime | String |

---

## Funcionalidades

- Lectura de temperatura.
- Lectura de humedad.
- Sincronización automática con Arduino Cloud.
- Dashboard remoto.
- Fecha y hora mediante NTP.

---

## Arquitectura

ESP32 → WiFi → Arduino IoT Cloud → Dashboard

---

## Autor

Alejandro José Espinal Torres
Maestría en Ingeniería de Software
