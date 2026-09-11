# Portafolio de Análisis de Datos - Telecomunicaciones

¡Bienvenido! Soy profesional en Redes y Telecomunicaciones con 15 años de experiencia en diseño, despliegues y mantenimiento de infraestructura masiva. Este espacio está dedicado a conectar la analítica de datos y la inteligencia artificial con la optimización de redes de planta externa.

## 🚀 Proyecto 1: Optimización Financiera y Operativa en Despliegues FTTH GPON

### 📋 1. Definición del Problema
En los despliegues masivos de fibra óptica (FTTH), la elección de la arquitectura de splitteo impacta directamente en los costos fijos (CAPEX) y operativos (OPEX). Este análisis evalúa matemáticamente qué distribución es más eficiente para una relación de división 1x64 en zonas urbanas:
* **Escenario A:** Primer nivel 1x8 y Segundo nivel 1x8 (Estándar habitual).
* **Escenario B:** Primer nivel 1x4 y Segundo nivel 1x16 (Alternativa de alta densidad).

### 📊 2. Variables Analizadas en el Modelo
* **Costos de Materiales:** Cantidad de cajas NAP necesarias por puerto OLT y splitters de segundo nivel.
* **Metraje de Cable Drop:** Longitud acumulada de las acometidas desde la caja NAP hasta el abonado según la dispersión geográfica.
* **Tiempos de Ejecución:** Horas-hombre requeridas por las cuadrillas para el sangrado, fusión y tendido de cables en postes.
* **Mantenimiento (OPEX):** Densidad de fallas por caja y saturación del espacio visual en postes municipales.

### 💡 3. Conclusión Preliminar del Análisis
* La distribución **1x4 + 1x16** reduce costos de CAPEX inicial al instalar la mitad de cajas NAP, pero incrementa significativamente el gasto en cable Drop y tiempos de instalación en zonas de baja o mediana densidad horizontal.
* La distribución **1x8 + 1x8** se mantiene como la solución óptima y equilibrada para despliegues masivos residenciales comunes.
