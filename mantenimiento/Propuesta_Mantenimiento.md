
#  Propuesta de Mantenimiento de Software

##  Proyecto: Calculadora de Presupuesto Mensual

### 1. Introducción
El mantenimiento de software es una fase fundamental del ciclo de vida del producto.  
En este proyecto, el mantenimiento busca **mejorar la usabilidad, rendimiento y presentación visual** de la calculadora de presupuesto mensual, con base en los principios de **Sommerville (2011)** y **Pressman (2010)**.

---

### 2. Tipos de mantenimiento de software
1. **Mantenimiento Correctivo:** Corrige errores en el cálculo o en la visualización de los resultados.  
   *Ejemplo:* resolver un fallo que impida mostrar correctamente el balance mensual.

2. **Mantenimiento Adaptativo:** Ajusta el software a nuevos entornos o navegadores.  
   *Ejemplo:* compatibilidad con nuevas versiones de Android o Windows.

3. **Mantenimiento Perfectivo:** Mejora la funcionalidad y apariencia del sistema.  
   *Ejemplo:* agregar gráficos o un sistema de categorización de gastos.

4. **Mantenimiento Preventivo:** Reduce el riesgo de errores futuros mediante la documentación y optimización del código.  
   *Ejemplo:* refactorizar funciones y mejorar comentarios del código.

---

### 3. Etapas del proceso de mantenimiento
Según **Sommerville**:
- Comprensión del programa.  
- Análisis del impacto.  
- Implementación del cambio.  
- Pruebas del sistema.  
- Entrega y liberación.

Según **Pressman**:
- Comprensión del problema.  
- Análisis de la solicitud de cambio.  
- Diseño.  
- Implementación y pruebas.  
- Liberación y aceptación.

---

### 4. Análisis del caso: Calculadora de Presupuesto Mensual
El sistema actual cumple con su función, pero presenta limitaciones:
- No clasifica los gastos o ingresos.  
- No genera reportes gráficos.  

#### Mejoras propuestas
- **Módulo de categorización automática** de ingresos y gastos.  
- **Visualización gráfica** mediante barras, pastel o líneas.  
- **Alertas automáticas** cuando una categoría supera el 30% del ingreso total.  
- **Exportación de reportes** en PDF o Excel.

Estas mejoras corresponden al **mantenimiento perfectivo**, ya que amplían las funciones del sistema.

---

### 5. Beneficios esperados
- Mayor claridad en la distribución del gasto.  
- Identificación rápida de áreas de consumo excesivo.  
- Experiencia visual más intuitiva.  
- Mejor planificación y control financiero.

---

### 6. Ejemplo de estimación de costos
| Tipo de mantenimiento | Frecuencia | Horas/Incidente | Costo/Hora | Costo mensual |
|------------------------|-------------|------------------|-------------|----------------|
| Correctivo | 4 | 10 | $50 | $2,000 |
| Adaptativo | 2 | 20 | $50 | $2,000 |
| Perfectivo | 1 | 40 | $50 | $2,000 |
| Preventivo | 1 | 15 | $50 | $750 |
| **Total estimado** |  |  |  | **$6,750** |

---

### 7. Conclusión y recomendaciones
El mantenimiento planificado permitirá mejorar la estabilidad, usabilidad y mantenibilidad del sistema.  
Se recomienda priorizar el **mantenimiento preventivo**, ya que evita degradaciones futuras del software y reduce los costos a largo plazo.  

Asimismo, se sugiere:
- Actualizar los costos y frecuencias periódicamente.  
- Aplicar métricas de calidad como la **complejidad ciclomática**.  
- Capacitar al equipo en mantenimiento correctivo y pruebas de regresión.
