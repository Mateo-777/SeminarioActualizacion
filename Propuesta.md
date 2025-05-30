<!-- Badges -->
![GitHub repo size](https://img.shields.io/github/repo-size/usuario/QuantumAgri)

## Proyecto: QuantumAgri - Optimización Cuántica de Cultivos para Pequeños Agricultores

### 1. Análisis del Problema
En regiones rurales vulnerables del departamento de Putumayo, los pequeños agricultores enfrentan múltiples desafíos que limitan su productividad y calidad de vida:

1. **Rendimientos agrícolas bajos y variabilidad de cultivos**  
   - Prácticas agrícolas tradicionales sin soporte de datos conducen a asignaciones ineficientes de semillas y fertilizantes.  
   - Fluctuaciones climáticas (lluvias intensas y períodos de sequía) sin un modelo predictivo generan pérdidas de hasta el 30% de la cosecha anual.  
   - Variabilidad de rendimiento entre parcelas adyacentes de hasta 20%, provocando desigualdades económicas.

2. **Escasez y gestión deficiente de recursos hídricos**  
   - Sistemas de riego manual en la mayoría de fincas, con uso de agua no monitoreado y desperdicio estimado de 25%.  
   - Infraestructura limitada: pozos artesanales sin medición de caudal, falta de sensores de humedad en tiempo real.

3. **Falta de acceso a información y tecnologías predictivas**  
   - Dependencia de pronósticos meteorológicos genéricos de estaciones lejanas (hasta 100 km), sin granularidad local.  
   - Ausencia de plataformas de toma de decisiones basadas en datos: los agricultores usan intuición o recomendaciones comerciales.

4. **Impacto socioeconómico y ambiental**  
   - Ingreso per cápita agrícola promedio inferior al 50% del salario mínimo nacional.  
   - Migración juvenil hacia áreas urbanas por falta de oportunidades rurales.  
   - Agotamiento de suelos por aplicación excesiva de fertilizantes sin análisis de pH o nutrientes.

#### Diagrama de Flujo del Problema y Necesidades
```mermaid
graph LR
  A[Variabilidad Climática] --> B[Incertidumbre en Siembra]
  C[Sistemas de Riego Manual] --> B
  B --> D[Reducción de Rendimientos]
  E[Falta de Datos Locales] --> B
  D --> F[Menor Ingreso]
  F --> G[Migración]
  D --> H[Seguridad Alimentaria]
