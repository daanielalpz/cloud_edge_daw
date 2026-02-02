# Tarea (c+d+e) · Edge, Fog, Mist y Cloud (DAW 1º)

## 🅲 Tarea C — Edge Computing y relación con Cloud
**Definición (3–5 líneas):**
Edge Computing es un modelo de computación en el que el procesamiento de datos se realiza lo más cerca posible del lugar donde se generan (sensores, dispositivos IoT, máquinas, etc.).
Su objetivo principal es reducir la latencia, el consumo de ancho de banda y la dependencia constante de la nube.
Permite respuestas más rápidas y eficientes en tiempo real.

**Relación Edge ↔ Cloud (5–8 líneas):**
Edge y Cloud no se sustituyen, sino que se complementan. El Edge se encarga de procesar datos críticos o inmediatos cerca del origen, mientras que la Cloud se utiliza para almacenamiento masivo, análisis avanzado y gestión centralizada. Los datos filtrados o resumidos en el Edge se envían a la Cloud para su análisis a largo plazo. De esta forma se optimizan recursos, se mejora el rendimiento y se reduce el tráfico de red.

**Ejemplo real:**
En una fábrica inteligente, los sensores de las máquinas detectan fallos en tiempo real usando Edge Computing. Solo los datos relevantes se envían a la Cloud para análisis históricos, mantenimiento predictivo y generación de informes.

**Fuentes oficiales (mín. 2):**
- Documentación de AWS sobre Edge Computing

- Microsoft Azure – Arquitectura Edge y Cloud

## 🅳 Tarea D — Fog vs Mist (niveles y zonas de aplicación)
**Definición Fog (2–4 líneas):**
Fog Computing es una capa intermedia entre Edge y Cloud. Permite procesar, almacenar y analizar datos en nodos cercanos a la red local, como routers o gateways. Reduce latencia y descarga trabajo de la nube.

**Definición Mist (2–4 líneas):**
Mist Computing es el nivel más cercano al hardware. El procesamiento se realiza directamente en sensores o microcontroladores con recursos muy limitados. Se centra en tareas simples y reacciones inmediatas.

**Esquema (ASCII o Mermaid recomendado):**
...

**Zonas de aplicación (qué hace cada capa):**
- Mist → Respuestas inmediatas en sensores (ej. activar una alarma).
- Edge → Procesamiento local rápido y toma de decisiones.
- Fog → Agregación de datos y control de redes locales.
- Cloud → Almacenamiento, análisis avanzado y gestión global.

## 🅴 Tarea E — Ventajas de la Cloud en sistemas conectados
Incluye mínimo 3 ventajas (recomendado 5), con explicación + ejemplo.

1) Ventaja: Escalabilidad
   Explicación: La Cloud permite aumentar o reducir recursos según la demanda sin cambiar la infraestructura física.
   Ejemplo: Una app IoT que recibe más usuarios puede aumentar servidores automáticamente.

2) Ventaja: Acceso remoto
   Explicación: Los datos y servicios están disponibles desde cualquier lugar con conexión a Internet.
   Ejemplo: Un administrador puede monitorizar sensores desde su portátil o móvil.
   
3) Ventaja: Almacenamiento masivo
   Explicación: La nube permite guardar grandes volúmenes de datos de forma segura y organizada.
   Ejemplo: Guardar históricos de datos de sensores durante años.
   
4) Ventaja: Alta disponibilidad
   Explicación: Los servicios Cloud suelen tener redundancia y copias de seguridad automáticas.
   Ejemplo: Si un servidor falla, otro sigue funcionando sin interrupción.

**Fuente oficial (mín. 1):**
- Google Cloud – Ventajas del Cloud Computing
  
## 📚 Fuentes (enlaces oficiales)
(Recopila aquí todos los enlaces oficiales usados)
AWS – Edge Computing
https://aws.amazon.com/es/edge/

Microsoft Azure – Edge Computing
https://azure.microsoft.com/es-es/solutions/edge-computing/

Cisco – Fog Computing
https://www.cisco.com/c/en/us/solutions/internet-of-things/fog-computing.html

Google Cloud – Cloud Computing
https://cloud.google.com/learn/what-is-cloud-computing
