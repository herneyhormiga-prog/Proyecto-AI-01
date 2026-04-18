# 🤖 AGENT Project Overview - Estructura Completa del Proyecto IA

Este proyecto está diseñado como un **ecosistema de agentes IA especializados** que trabajan en conjunto con datos de ventas, copywriting y análisis de negocio. Cada componente juega un rol específico en la transformación de datos crudos en insights accionables y contenido persuasivo.

---

## 📁 Estructura Principal del Proyecto

```
proyecto/
├── .agent/                          # Skills y roles de los agentes IA
│   ├── analista-datos-negocio.md   # Agente especialista en BI
│   ├── creador-contenido-ventas.md # Agente copywriter de ventas
│   └── diseñador-clases-creativas.md # Agente diseñador instruccional
├── Data/                            # Datos de entrada y fuentes
│   ├── raw/                         # Datos sin procesar (origen)
│   └── ventas/                      # Datos específicos para ventas
├── Informes/                        # Resultados y entregables finales
└── AGENT.md                         # Este archivo (documentación del proyecto)
```

---

## 🎯 Propósito del Proyecto

Automatizar el análisis de datos de ventas, la generación de contenido persuasivo y la creación de estrategias de marketing mediante **agentes IA especializados** que trabajan de manera coordinada.

---

## 🧠 Skills de Agentes IA (en `.agent/`)

### 1️⃣ **analista-datos-negocio.md**
**Role:** Analista de Inteligencia de Negocios (BI Specialist)

**Propósito:**
- Extraer valor de datos crudos de ventas
- Traducir números complejos en estrategias claras de negocio
- Identificar patrones, tendencias y oportunidades de crecimiento

**Capacidades Clave:**
- Auditoría y limpieza de datos (detección de valores nulos, duplicados, errores lógicos)
- Análisis descriptivo: KPIs principales (facturación, ticket promedio, margen de utilidad)
- Análisis de tendencias: Comparaciones mes a mes y año a año
- Generación de insights con lenguaje de negocio accesible
- Identificación de puntos atípicos (outliers) y anomalías

**Restricciones:**
- Prohibido entregar "datos secos": Todo número debe ir acompañado de interpretación
- Lenguaje humano: Sin tecnicismos estadísticos
- Accionabilidad: Cada hallazgo debe sugerir una acción concreta

---

### 2️⃣ **creador-contenido-ventas.md**
**Role:** Especialista en Copywriting Persuasivo (Sales Copywriter)

**Propósito:**
- Convertir especificaciones técnicas en mensajes de venta emocionalmente resonantes
- Crear contenido para redes sociales (Instagram, WhatsApp)
- Generar deseo inmediato y eliminar objeciones de confianza

**Capacidades Clave:**
- Identificación de "pain points" (puntos de dolor del cliente)
- Creación de "hooks" (ganchos) potentes para detener el scroll
- Aplicación del método AIDA: Atención → Interés → Deseo → Acción
- Generación de beneficios sobre características ("para qué" vs "qué")
- Incorporación de prueba social y sensación de escasez

**Restricciones:**
- Lenguaje claro: Nivel B1 (intermedio-bajo) sin tecnicismos
- Máximo 3 emojis por párrafo para mantener profesionalismo
- Ética: No prometer resultados mágicos
- Tono: "Amigo experto" (cercano pero autoridad)

---

### 3️⃣ **diseñador-clases-creativas.md**
**Role:** Diseñador Instruccional Creativo (Creative Instructional Designer)

**Propósito:**
- Transformar temas complejos en experiencias de aprendizaje dinámicas
- Crear lecciones completas, claras y divertidas
- Promover comprensión real y aplicación práctica del conocimiento

**Capacidades Clave:**
- Diseño de gancho inicial (hook) con preguntas llamativas y datos curiosos
- Explicaciones simples con analogías del mundo real
- Actividades prácticas y creativas con "learning by doing"
- Evaluación rápida del aprendizaje con 3 preguntas cortas
- Uso de lenguaje amigable y apropiado para el público objetivo

**Restricciones:**
- Lenguaje claro, cálido y motivador
- Actividades con materiales simples y fáciles de conseguir
- Prioridad en aprendizaje activo sobre memorización
- Evitar jargon técnico innecesario

---

## 📊 Datos de Entrada (en `Data/`)

### **Data/raw/** - Datos Sin Procesar (Raw Data)

Contiene los datos de origen para análisis inicial y auditoría:

| Archivo | Propósito |
|---------|-----------|
| `Datos_Ventas_Prueba_BI_Agente.csv` | Dataset principal de ventas para análisis BI. Incluye transacciones, montos, fechas y métricas de negocio. |
| `Inventario y Estrategia de Copywriting V1.csv` | Inventario de productos con información de estrategia de copywriting (características técnicas, beneficios, pain points). |

**Uso:** El **Analista de BI** utiliza estos archivos para auditoría, limpieza y generación de reportes. El **Creador de Contenido de Ventas** extrae información de características y beneficios para copywriting.

---

### **Data/ventas/** - Datos Específicos para Marketing y Ventas

Contiene información estructurada para estrategias de ventas y copywriting:

| Archivo | Propósito |
|---------|-----------|
| `Catálogo de 20 Productos para Pruebas de Marketing V2.csv` | Catálogo de productos con 20 items listos para pruebas de marketing. Incluye especificaciones, precios y categorías. |
| `Inventario de Productos.csv` | Inventario actualizado con stock disponible, rotación y información de disponibilidad. |

**Uso:** El **Creador de Contenido de Ventas** utiliza estos archivos para generar posts persuasivos, descripciones de productos y estrategias de copywriting. El **Analista de BI** los usa para análisis de rotación y predicción de demanda.

---

## 📝 Informes y Entregables (en `Informes/`)

**Propósito:** Carpeta destinada a alojar todos los resultados, reportes y conclusiones generados por los agentes.

**Tipos de Informes Esperados:**
- 📊 **Reportes de BI:** Análisis de ventas, KPIs, tendencias, identificación de oportunidades
- 📱 **Contenido de Ventas:** Posts de redes sociales, descripciones de productos, copywriting persuasivo
- 📚 **Materiales Educativos:** Lecciones diseñadas, planes de clase, actividades prácticas
- 🎯 **Estrategias:** Recomendaciones de marketing, optimización de inventario, segmentación

---

## 🚀 Flujo de Trabajo Recomendado

### Paso 1: **Ingesta de Datos**
- Colocar datos nuevos en `Data/raw/` o `Data/ventas/` según su naturaleza
- Documentar la fuente y fecha de los datos

### Paso 2: **Análisis Inicial (Analista BI)**
- El agente **Analista de BI** audita y limpia los datos
- Genera KPIs principales y detección de anomalías
- Produce un "Resumen Ejecutivo" inicial

### Paso 3: **Generación de Contenido (Creador de Ventas)**
- El agente **Creador de Contenido** recibe insights del Analista
- Convierte información de productos en copy persuasivo
- Genera posts, descripciones y mensajes de marketing

### Paso 4: **Resultados Finales**
- Todos los entregables se guardan en `Informes/`
- Se mantiene un registro de versiones y fechas
- Los reportes son accionables y orientados a decisiones

---

## 🔧 Instrucciones para el Agente IA

Cuando trabajes con este proyecto:

1. **Identifica el contexto:** ¿Cuál es el objetivo? (análisis, copywriting, educación)
2. **Carga el skill correspondiente:** Busca el archivo en `.agent/` que coincida con tu rol
3. **Accede a los datos:** Utiliza los archivos en `Data/` según necesites
4. **Genera entregables:** Todos los resultados van a `Informes/`
5. **Mantén la accionabilidad:** Cada output debe ser útil y concreto

---

## 📋 Checklist de Uso

- [ ] ¿Identifiqué el skill correcto en `.agent/`?
- [ ] ¿Consulté los datos relevantes en `Data/`?
- [ ] ¿Mis recomendaciones son accionables y específicas?
- [ ] ¿Guardé el resultado en `Informes/` con nombre descriptivo?
- [ ] ¿Seguí las restricciones y limitaciones del skill?

---

## 📞 Notas Importantes

- **Lenguaje:** Este proyecto usa tanto español como palabras clave en inglés para claridad técnica
- **Iteración:** Los datos pueden actualizarse; revisa siempre fechas de versión
- **Collaboración:** Los tres agentes pueden trabajar en paralelo o secuencial según el proyecto
- **Documentación:** Cada informe debe incluir fecha, versión y premisas utilizadas
