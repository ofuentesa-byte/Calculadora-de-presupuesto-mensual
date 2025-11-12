
#  Calculadora de Presupuesto Mensual

##  Descripción del caso
La **Calculadora de Presupuesto Mensual** es una aplicación de software que permite registrar los ingresos y gastos mensuales de un usuario, calcular automáticamente el balance y mostrar una recomendación según el resultado.  
Su objetivo es ofrecer una herramienta sencilla y práctica para el control financiero personal, ideal para estudiantes y trabajadores que deseen organizar sus finanzas de manera digital.

---

##  Objetivos
- Desarrollar una aplicación funcional para calcular presupuestos personales mensuales.  
- Aplicar principios de ingeniería de software: requerimientos, pruebas y mantenimiento.  
- Incorporar control de versiones con Git y GitHub.  
- Documentar el proyecto en formato Markdown.  

---

##  Requerimientos principales

### Requerimientos funcionales
1. Permitir ingresar montos de ingresos y gastos.  
2. Calcular el balance mensual (ingresos - gastos).  
3. Mostrar un mensaje según el resultado:  
   - *Balance positivo → “Buen manejo del presupuesto.”*  
   - *Balance negativo → “Reduzca gastos innecesarios.”*  
4. Permitir limpiar los campos para realizar un nuevo cálculo.  

### Requerimientos no funcionales
1. Interfaz clara y fácil de usar.  
2. Respuesta rápida al cálculo.  
3. Compatibilidad multiplataforma (Windows y Android).  
4. Diseño simple y con retroalimentación visual.  

---

##  Tabla de pruebas funcionales

| **Caso de prueba** | **Entrada** | **Resultado esperado** | **Validación** |
|--------------------|-------------|------------------------|----------------|
| **CP1 - Balance positivo** | **Ingresos:** 800  <br> **Gastos:** 400 | Muestra **“Balance positivo: 400”** en color verde | ✅ Correcto |
| **CP2 - Balance negativo** | **Ingresos:** 500  <br> **Gastos:** 900 | Muestra **“Reduzca gastos innecesarios”** en color rojo | ✅ Correcto |
| **CP3 - Campos vacíos** | **Ingresos:** *(vacío)*  <br> **Gastos:** *(vacío)* | Muestra mensaje de advertencia **“Complete todos los campos”** | ✅ Correcto |

---

##  Tipo de mantenimiento propuesto

### **Mantenimiento Perfectivo**
Este mantenimiento se centra en **mejorar la experiencia del usuario y ampliar las funciones del sistema**, sin alterar su propósito principal.  

**Mejoras implementadas o sugeridas:**
- Categorización automática de ingresos y gastos.  
- Gráficos visuales (barras o pastel).  
- Exportación de resultados en PDF y Excel.  

Estas mejoras optimizan la funcionalidad y usabilidad del software, incrementando su valor y mantenibilidad.

---

##  Reflexión sobre el control de versiones

El **control de versiones** permite gestionar los cambios de un proyecto de software a lo largo del tiempo, conservando su historial y evitando pérdidas de información.  
Es esencial en la ingeniería de software, ya que facilita la **colaboración, la trazabilidad y la restauración de versiones previas** cuando se cometen errores.

### Tipos de sistemas de control de versiones

1. **Sistemas locales**  
   - Cada desarrollador registra los cambios en su propio equipo.  
   -  *Ventajas:* simplicidad y rapidez.  
   -  *Desventajas:* poca colaboración y riesgo de pérdida de datos.

2. **Sistemas centralizados**  
   - Un servidor principal almacena el repositorio completo.  
   -  *Ventajas:* control central y seguridad.  
   -  *Desventajas:* dependencia del servidor y de la conexión.  
   -  *Ejemplo:* Subversion (SVN).

3. **Sistemas distribuidos**  
   - Cada usuario tiene una copia completa del repositorio, incluyendo el historial.  
   -  *Ventajas:* trabajo sin conexión, colaboración flexible y mayor velocidad.  
   -  *Ejemplo:* **Git**.

### Elementos y operaciones básicas en Git

- **Repositorio:** almacén del historial completo del proyecto.  
- **Working Copy:** copia local donde el desarrollador realiza cambios.  
- **Commit:** guarda los cambios en el historial del repositorio.  
- **Log:** muestra la lista de cambios y autores.  
- **Checkout:** permite cambiar de rama o versión.  
- **Push / Pull:** sincroniza los cambios entre local y remoto.  
- **Branch:** crea una línea paralela de desarrollo para nuevas funciones.

### GitHub en el proyecto
GitHub, basado en Git, fue fundamental en este proyecto para:  
- Centralizar los documentos y versiones del sistema.  
- Registrar commits descriptivos para cada entrega.  
- Visualizar el historial de cambios (por ejemplo, entre *DRS_v1* y *DRS_v2*).  
- Integrar documentación en formato Markdown (.md), mejorando la legibilidad y colaboración.  

 En conclusión, el control de versiones fue clave para **mantener un flujo de trabajo ordenado, colaborativo y trazable**, asegurando la integridad y calidad del software durante todo su ciclo de vida.

---

##  Autor

**Oswaldo Geampierre Fuentes Abril**  



