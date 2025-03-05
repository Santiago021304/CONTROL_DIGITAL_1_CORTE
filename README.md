# Control de Movimiento

## Introducción
Este documento proporciona una introducción a los sistemas de control de movimiento, enfocándose en servomotores y motores eléctricos. Explica la importancia de los sistemas de control para regular la posición, velocidad y torque de un motor.

## Tipos de Motores
### Motores de Corriente Continua (DC)
- Descripción de su estructura: estator, rotor y colector de delgas.
- Aplicaciones en la industria.

### Motores de Corriente Alterna (AC)
#### Motores Síncronos
- Funcionamiento basado en la sincronización con la frecuencia de la red eléctrica.
- Aplicaciones industriales.

#### Motores Asíncronos
- Principio de inducción electromagnética.
- Aplicaciones industriales.

## Comparación de Motores
| Tipo de Motor | Ventajas | Desventajas |
|--------------|----------|------------|
| DC | Control simple, bajo costo, alta eficiencia en aplicaciones pequeñas | Requiere mantenimiento, imanes pueden desmagnetizarse |
| AC Síncrono | Alta eficiencia, poco mantenimiento | Control más complejo, requiere sincronización |
| AC Asíncrono | Robustos, excelente resistencia al entorno | Menor eficiencia en pequeñas aplicaciones |

## Modelado de Motores
- Presentación de ecuaciones matemáticas para modelar motores DC.
- Implementación de modelos en MATLAB/Simscape.

## Sensores en Servomecanismos
### Encoders
- **Absolutos**: Proporcionan una posición absoluta.
- **Incrementales**: Generan pulsos por unidad de movimiento.

### Resolver
- Sensor analógico de posición angular.
- Similar a un transformador.

### Medición de Torque
- Uso de sensores de corriente para inferir torque.

## Drivers de Potencia
- Amplifican señales de control para alimentar motores.
- Uso de **modulación por ancho de pulso (PWM)**.
- Implementación con **L293 y L298**.

## Simulaciones y Validación
- Modelado de motores en **Simscape (MATLAB)**.
- Comparación de simulaciones con datos reales.

## Control de Torque y Conversión de Energía
- Métodos de control de torque en motores DC.
- Explicación de inversores y modulación **SPWM** para variación de velocidad.

## Bibliografía
- CHAPMAN (2005). "Máquinas eléctricas". McGraw-Hill.
- LANGSDORF (1968). "Principios de las máquinas de corriente continua". McGraw-Hill.
- SERRANO IRIBARNEGARAY (1989). "Fundamentos de máquinas eléctricas rotativas". Marcombo.
- Variadores de Siemens: [Enlace](https://www.swe.siemens.com/spain/web/es/industry/drive_tech/variadores/Pages/Variadores.aspx)
- Motores de corriente continua: [Enlace](https://www.areatecnologia.com/electricidad/motores-corriente-continua.html)

---
**Autor:** Ing. Jorge Eduardo Cote MSc.
