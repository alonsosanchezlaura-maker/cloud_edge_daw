# Tarea (c+d+e) · Edge, Fog, Mist y Cloud (DAW 1º)

## 🅲 Tarea C — Edge Computing y relación con Cloud
**Definición (3–5 líneas):**

Edge Computing es un modelo de computación donde el procesamiento de datos se realiza lo más cerca posible de la fuente que los genera (sensores, dispositivos IoT, cámaras, etc.).
En lugar de enviar todos los datos a la nube, el edge filtra, analiza o toma decisiones locales.
Esto reduce la latencia, el consumo de ancho de banda y mejora la privacidad y la respuesta en tiempo real.

**Relación Edge ↔ Cloud (5–8 líneas):**

El Edge de nube es un paradigma informático que lleva el cloud computing al Edge de la red. Con el auge del Internet de las cosas (IoT), la inteligencia artificial, los vehículos autónomos y otras tecnologías, las organizaciones necesitan poder procesar enormes cantidades de datos, a la vez que reducen la latencia y mantienen una alta disponibilidad. El Cloud Edge Computing ofrece esta capacidad, ya que sitúa los recursos de nube más cerca de los lugares donde se crean y utilizan los datos, por lo que se elimina la necesidad de redirigir los datos a través de centros de datos centralizados situados en ubicaciones lejanas.

**Ejemplo real:**

En una fábrica inteligente, los sensores detectan vibraciones anómalas en una máquina.
El edge analiza los datos en tiempo real y detiene la máquina si hay riesgo.
La cloud recibe los datos históricos para análisis predictivo y mantenimiento a largo plazo.

**Fuentes oficiales (mín. 2):**

AWS — What is Edge Computing?
https://aws.amazon.com/what-is/edge-computing/

(https://www.akamai.com/es/glossary/what-is-cloud-edge-computing#:~:text=%C2%BFQu%C3%A9%20es%20CloudEdge%3F,seguridad%20en%20su%20dispositivo%20m%C3%B3vil.)

## 🅳 Tarea D — Fog vs Mist (niveles y zonas de aplicación)
**Definición Fog (2–4 líneas):**
Fog Computing es una capa intermedia entre el edge y la cloud.
Se sitúa normalmente en gateways, routers o servidores locales.
Permite coordinar varios dispositivos edge y procesar datos antes de enviarlos a la nube.

**Definición Mist (2–4 líneas):**
Mist Computing lleva el procesamiento al nivel más bajo posible: el propio dispositivo o sensor.
Realiza microdecisiones muy simples con recursos mínimos.
Es ideal para respuestas ultrarrápidas y funcionamiento incluso sin conexión.

**Esquema (ASCII o Mermaid recomendado):**
[ Sensor / Dispositivo ]
           ↓
         Mist
           ↓
         Edge
           ↓
          Fog
           ↓
         Cloud



**Zonas de aplicación (qué hace cada capa):**
- Mist → decisiones básicas en el sensor (umbral superado, activación/desactivación).
- Edge → procesamiento local más complejo (filtrado, análisis rápido, control inmediato).
- Fog → agregación y coordinación de varios edge, reglas locales, continuidad del servicio.
- Cloud → almacenamiento masivo, analítica avanzada, IA, gestión global del sistema.

## 🅴 Tarea E — Ventajas de la Cloud en sistemas conectados
Incluye mínimo 3 ventajas (recomendado 5), con explicación + ejemplo.

1) Ventaja: ...
   Explicación: ...
   Ejemplo: ...

2) Ventaja: ...
   Explicación: ...
   Ejemplo: ...

3) Ventaja: ...
   Explicación: ...
   Ejemplo: ...

**Fuente oficial (mín. 1):**
- ...

## 📚 Fuentes (enlaces oficiales)
(Recopila aquí todos los enlaces oficiales usados)
