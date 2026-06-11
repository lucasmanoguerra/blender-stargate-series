---
name: screenplay-structurer
description: Estructura guiones cinematográficos profesionales para producción en Blender. Workflow completo desde logline hasta desglose de escenas con notas de cámara, iluminación y VFX. Ideal para series hiperrealistas.
license: MIT
compatibility: opencode
metadata:
  workflow: screenwriting
  output: screenplay
  format: markdown
---

# Screenplay Structurer

## Propósito

Esta skill guía la creación de guiones cinematográficos profesionales desde cero, diseñada específicamente para producción hiperrealista en **Blender**. Workflow paso a paso que cubre:

1. **Logline y premisa** — el concepto central en 1-2 oraciones
2. **World-building** — reglas del universo, facciones, tecnología, línea temporal
3. **Personajes** — fichas completas con arcos, relaciones y referencias visuales
4. **Estructura episódica** — arco de serie, temporada, episodios, beat sheet
5. **Desglose de escenas** — escena por escena con métrica de producción
6. **Plan de cinematografía** — cámara, iluminación, atrezo, VFX para Blender

## Cuándo usarla

- Cuando necesites **estructurar un guión desde cero**
- Cuando quieras **desarrollar una serie o película** con metodología profesional
- Cuando vayas a **producir en Blender** y necesites planificar aspectos visuales
- Cuando trabajes con **franquicias existentes** (universos expandidos, reboots, continuaciones)

## Cómo usar esta skill

Ejecútala y sigue el flujo. La skill te irá guiando paso a paso con preguntas y templates. No es necesario completar todo de una vez: cada paso genera un archivo en `templates/` que puedes retomar después.

### Convenciones de formato

- **Logline**: 1-2 oraciones. Debe contener: protagonista, conflicto, objetivo, stakes.
- **Sinopsis**: 1-2 párrafos por episodio. Sin spoilers del arco completo.
- **Treatment**: Escenas numeradas, sin diálogo completo, con intención dramática.
- **Guión técnico**: Escenas con formato: `INT/EXT. LOCACIÓN - DÍA/NOCHE`, acción, diálogo.
- **Notas Blender**: `[BLENDER]` al inicio del bloque, especificando: cámara, iluminación, materiales, VFX.

### Estructura de archivos

```
.opencode/skills/screenplay-structurer/
├── SKILL.md
├── templates/
│   ├── 01-logline.md
│   ├── 02-world-building.md
│   ├── 03-personajes.md
│   ├── 04-estructura.md
│   ├── 05-escenas.md
│   └── 06-cinematografia.md
└── references/
    └── stargate-universe.md
```

Los archivos de salida se generan en el directorio de trabajo del usuario.

---

## Workflow detallado

### Paso 1: Logline y premisa

Usa el template `01-logline.md`. Pregunta al usuario:

- **Género principal** (ciencia ficción, drama, acción, thriller, etc.)
- **Protagonista** (rol, objetivo, conflicto interno/externo)
- **Conflicto central** (qué amenaza o misterio impulsa la trama)
- **Stakes** (qué se pierde si falla)
- **Tono** (realista, épico, íntimo, humorístico)
- **Conexión con universo existente** (si aplica: precuela, secuela, spin-off, reboot)

### Paso 2: World-building

Usa el template `02-world-building.md`. Define:

- **Estado del mundo / universo** al inicio de la historia
- **Reglas establecidas** (tecnología, magia, física, limitaciones)
- **Facciones / civilizaciones** (aliados, enemigos, neutrales)
- **Línea temporal** (eventos clave antes de la historia)
- **Mapa de locaciones** (planetas, estaciones, naves clave)

Para continuaciones de franquicias, usar `references/` como guía y expandir desde ahí.

### Paso 3: Personajes

Usa el template `03-personajes.md`. Para cada personaje:

- **Datos básicos**: nombre, edad, rol, afiliación
- **Personalidad**: rasgos, motivaciones, miedos, defectos
- **Historia previa**: origen, eventos formativos
- **Arco en la serie**: cómo evoluciona
- **Relaciones**: vínculos con otros personajes
- **Referencia visual**: descripción física para modelado en Blender
- **Voz**: forma de hablar, expresiones características
- **Concept art notes**: paleta de colores, silueta, vestuario

### Paso 4: Estructura episódica

Usa el template `04-estructura.md`. Define:

- **Arco de serie**: el viaje completo en una frase
- **Temporada actual**: premisa de la temporada
- **Episodios**: lista numerada con:
  - Título provisional
  - Logline del episodio
  - Protagonista(s) del episodio
  - A/B/C stories
  - Cliffhanger (si aplica)
- **Beat sheet por episodio**: Opening, inciting incident, midpoint, climax, resolution

### Paso 5: Desglose de escenas

Usa el template `05-escenas.md`. Para cada escena:

- **Encabezado**: `INT/EXT. LOCACIÓN - DÍA/NOCHE`
- **Personajes presentes**
- **Acción**: qué ocurre visualmente
- **Diálogo clave** (sin escribir el guión completo aún)
- **Props necesarios**
- **Duración estimada** en segundos
- **Notas de producción Blender**: qué necesita ser modelado, texturizado, animado

### Paso 6: Plan de cinematografía (Blender)

Usa el template `06-cinematografia.md`. Para escenas clave:

- **Tipo de plano**: Close-up, Medium, Wide, POV, Over-shoulder, Dolly, Crane, etc.
- **Movimiento de cámara**: estática, pan, tilt, tracking, handheld, steadycam
- **Lente simulada**: focal (mm), apertura, profundidad de campo
- **Iluminación**: esquema de luces (3-point, natural, dramática), temperatura de color, HDRIs
- **Composición**: regla de tercios, leading lines, color grading reference
- **Referencia visual**: links a imágenes de referencia o descripción
- **Notas técnicas Blender**:
  - `[CAMERA]` — cámara, lente, DOF, resolución
  - `[LIGHTS]` — tipo, intensidad, color, posición
  - `[MATERIALS]` — shaders clave, texturas procedurales
  - `[VFX]` — compositing, particles, smoke, fire, greenscreen
  - `[RENDER]` — cycles/eevee, samples, denoising, post-pro

---

## Reglas de calidad

1. **Todo debe ser producible en Blender**. Si algo no se puede hacer, se rediseña.
2. **Las referencias visuales son obligatorias** para cada escena clave. Sin referencia, no se construye.
3. **Los personajes deben tener arco**. Si un personaje no cambia en la temporada, se fusiona o se elimina.
4. **Cada episodio debe tener un gancho** que conecte al siguiente.
5. **El world-building debe ser consistente**. Si se introduce una regla, no se rompe sin consecuencias.
6. **Formato profesional de guión**: encabezados de escena normalizados, acción en presente, diálogo con personaje en mayúsculas.

---

## Output final

Al completar el workflow, el proyecto debe contener:

```
series/
├── 00-bible/
│   ├── logline.md
│   ├── world-building.md
│   ├── personajes/
│   │   ├── protagonista-01.md
│   │   ├── antagonista-01.md
│   │   └── secundarios.md
│   └── timeline.md
├── season-01/
│   ├── estructura.md
│   ├── episode-01/
│   │   ├── beat-sheet.md
│   │   ├── escenas.md
│   │   ├── cinematografia.md
│   │   └── screenplay.md
│   ├── episode-02/
│   └── ...
└── blender/
    ├── assets.md            # Lista de assets a modelar
    ├── shots-list.md        # Lista maestra de planos
    └── render-queue.md      # Plan de renderizado por escena
```

---

## Notas para el agente

- Pregunta **una cosa a la vez**. No abrumes al usuario con 10 preguntas seguidas.
- Después de cada paso, muestra un **resumen** de lo que se generó y pide confirmación antes de avanzar.
- Si el usuario se desvía del tema, vuelve amablemente al workflow.
- Usa los templates como **guía mínima**, no como restricción. Si el usuario quiere profundizar más en algo, permíteselo.
- Para proyectos de franquicia, primero consulta `references/` para mantener consistencia canónica.
