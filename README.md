# Diseño PCB LPC845 - Proyecto KiCAD

Este repositorio contiene el proyecto de diseño de PCB realizado en KiCAD para el microcontrolador **LPC845**. La placa está diseñada para soportar tanto el [**dashboard de visualización de datos**](https://github.com/AguileraGabriel/TD2-Dashboard-Termohigrometro.git) como el código para la [**Herramienta de Medición de Salto Térmico**](https://github.com/AguileraGabriel/Proyecto-Termohigrometro.git).

---

## Descripción

El objetivo de este proyecto es ofrecer una solución de hardware que integre todas las funcionalidades necesarias para:
- **Dashboard de Visualización de Datos:** Permite visualizar de forma gráfica y en tiempo real los datos obtenidos por el LPC845.
- **Herramienta de Medición de Salto Térmico:** Facilita el análisis de la medición diferencial de temperatura, utilizando sensores como termistores y el SHT30 para obtener datos de temperatura, humedad y punto de rocío.

El diseño de la PCB asegura una integración óptima del LPC845 con los periféricos y sensores requeridos, permitiendo su uso en entornos de taller y de campo para pruebas y diagnóstico.

---

## Características

- **Microcontrolador LPC845:**  
  Gestiona la adquisición de datos y la comunicación con ambos sistemas (dashboard y herramienta de medición).

- **Compatibilidad Dual:**  
  La placa es compatible tanto con el dashboard desarrollado en C# como con el código de la Herramienta de Medición de Salto Térmico.

- **Integración de Sensores:**  
  - **SHT30:** Para la medición de temperatura, humedad y punto de rocío.
  - **Termistores NTC:** Para la medición diferencial de temperatura.
  - **RTC:** Para el registro del tiempo y envio sincronizado. 

- **Interfaces de Comunicación:**  
  Incluye conexiones para UART y otros protocolos necesarios para la transmisión de datos.

---

