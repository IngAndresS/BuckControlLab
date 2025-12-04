# BuckControlLab

**Plataforma educativa CHIL para validación de convertidor DC-DC tipo Buck**

## 📄 Descripción

BuckControlLab es una herramienta educativa desarrollada para facilitar la enseñanza y validación de convertidores de potencia tipo Buck mediante la metodología **Control Hardware-in-the-Loop (CHIL)**. Permite analizar, simular y ejecutar en tiempo real un convertidor Buck controlado digitalmente, usando la tarjeta **LAUNCHXL-F28379D** junto con MATLAB/Simulink y código generado automáticamente mediante Embedded Coder.

La plataforma incluye:

- Modelo promediado del convertidor Buck en Simulink.  
- Controlador PI discretizado (ajustado con PID Tuner).  
- Configuración de periféricos (ADC, ePWM) para microcontroladores C2000.  
- Flujo completo: modelo → código → hardware → adquisición de señales reales.  
- Interfaz amigable para facilitar su uso en entornos académicos.  
- Casos de estudio con diferentes condiciones de carga, referencia y potencia.  
- Herramientas para comparar resultados offline (simulación) vs. online (tiempo real).
- Video explicativo de como usar la app

Este repositorio contiene todos los recursos necesarios: modelos, scripts, interfaz, documentación, video explicativo y resultados de pruebas.

---

## 📂 Estructura del repositorio

