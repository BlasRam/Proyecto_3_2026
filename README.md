# Sistema Experimental para el Monitoreo de la Calidad del Aire Interior (IAQ) y Variables Ambientales con Comunicación LoRa

## Descripción

Este repositorio contiene el desarrollo de un sistema experimental para el monitoreo de la calidad del aire interior (IAQ) y variables ambientales, con capacidad de comunicación inalámbrica mediante tecnología LoRa.

El proyecto está orientado al diseño y validación de una plataforma electrónica basada en **ESP32-S3**, integrando sensado ambiental, adquisición de señales, supervisión energética y transmisión de datos. La propuesta busca servir como base para futuras pruebas de hardware, adquisición de datos ambientales y validación de un sistema completo de monitoreo IAQ.

## Objetivo

Desarrollar una plataforma experimental capaz de:

- monitorear variables asociadas a la calidad del aire interior
- adquirir variables ambientales complementarias
- supervisar el estado energético del sistema
- transmitir información de manera inalámbrica mediante LoRa
- servir como base para futuras etapas de validación y escalabilidad

## Características principales

- Microcontrolador **ESP32-S3**
- Monitoreo de calidad del aire interior (**IAQ**)
- Medición de variables ambientales
- Comunicación **LoRa**
- Supervisión de batería y alimentación
- Diseño electrónico propio en desarrollo
- Arquitectura modular y escalable

## Estado del proyecto

Actualmente el proyecto se encuentra en etapa de:

- desarrollo del esquemático electrónico
- selección e integración de componentes
- definición de arquitectura de alimentación y comunicaciones
- preparación para diseño de PCB
- consolidación del prototipo experimental

## Arquitectura general

El sistema contempla los siguientes bloques principales:

- **Unidad de control:** ESP32-S3
- **Sensado ambiental e IAQ:** sensores para calidad del aire y variables ambientales
- **Comunicación inalámbrica:** módulo LoRa
- **Supervisión energética:** monitoreo de batería y consumo
- **Alimentación:** entrada USB, batería recargable y regulación de voltaje
- **Expansión:** puertos auxiliares para futuras integraciones

## Tecnologías y módulos considerados

Dependiendo de la iteración del prototipo, el sistema contempla o evalúa componentes como:

- **ESP32-S3-WROOM-1**
- **RFM95CW** o **RYLR998** para comunicación LoRa
- **ENS160 / AHT2X** para IAQ y variables ambientales
- **ADS1015** para adquisición analógica adicional
- **MAX17048** para monitoreo de batería
- **TP4056** para carga de batería
- reguladores de 3.3 V para alimentación estable del sistema

## Estructura del repositorio

```text
/
├── docs/              # Documentación del proyecto
├── hardware/          # Esquemáticos, PCB, librerías y archivos de diseño
├── firmware/          # Código fuente del microcontrolador
├── images/            # Diagramas, capturas y recursos gráficos
├── datasheets/        # Hojas de datos de los componentes utilizados
└── README.md          # Descripción general del proyecto
