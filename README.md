<p align="center">
  <img src="https://img.shields.io/badge/Estado-En%20desarrollo-yellow" alt="Estado">
  <img src="https://img.shields.io/badge/Episodios-39%20%2F%203%20temporadas-blue" alt="Episodios">
  <img src="https://img.shields.io/badge/Formato-Guiones%20profesionales-green" alt="Formato">
  <img src="https://img.shields.io/badge/Producción-Blender%20hiperrealista-orange" alt="Blender">
</p>

<h1 align="center">⨁ STARGATE: DESTINY</h1>
<p align="center"><i>La continuación que Stargate Universe merecía.</i></p>
<p align="center">3 temporadas · 39 episodios · 21,000+ líneas de guión</p>

---

<p align="center">
<a href="#-la-historia">📖 La historia</a> •
<a href="#-temporadas">📺 Temporadas</a> •
<a href="#-cómo-contribuir">🤝 Cómo contribuir</a> •
<a href="#-estructura-del-repositorio">📁 Estructura</a> •
<a href="#-producción-en-blender">🎬 Producción</a>
</p>

---

## 📖 La historia

> *Diez años después de que la Destiny se perdiera en el borde del universo conocido, la Tierra establece una conexión interestelar permanente con la nave y descubre que **Eli Wallace sigue vivo** — ha pasado 8 años despierto, solo, reparando la nave, envejeciendo, cambiando.*
>
> *La Destiny ha cruzado galaxias siguiendo un mapa dejado por las naves sembradoras. Al final del viaje: un código fuente cosmológico incrustado en el tejido del universo desde antes del Big Bang. Pero una civilización más antigua que los Antiguos — **Los Curadores** — lleva eones eliminando a quienes se acercan demasiado a la verdad.*

**Stargate: Destiny** es una secuela directa de *Stargate Universe*, diseñada desde cero para producción hiperrealista en **Blender**. Combina el espíritu de exploración de SG-1 con la profundidad psicológica de Universe y el realismo científico de *The Expanse*.

---

## 📺 Temporadas

### Temporada 1: *El Despertar*
*El reencuentro. Eli solo durante 8 años. La lucha de Carter contra el IOA. Los fracasos de McKay. La advertencia de Daniel. La conexión.*

| Bloque | Episodios | Descripción |
|--------|-----------|-------------|
| **Eli** | E1–E4 | 8 años de soledad: pánico, aceptación, los "temblores", la pared de días |
| **Tierra** | E5–E8 | Carter vs. IOA, McKay fracasa, Daniel descubre la advertencia en Atlantis |
| **La Señal** | E9–E11 | 10 segundos. 47 segundos. La Superge. La conexión permanente. |
| **Reencuentro** | E12–E13 | Keller evalúa a Eli. La bifurcación. Los Curadores. |

### Temporada 2: *El Mapa*
*La Destiny sigue el mapa de las sembradoras. Los fragmentos del código fuente. Los Curadores. "Ella".*

| Bloque | Episodios | Descripción |
|--------|-----------|-------------|
| **Asentamiento** | E1–E4 | El equipo se instala. La zona muerta. Los constructores. |
| **Fragmentos** | E5–E8 | El código elige a Petrova y Hawkins. El Coro se divide. |
| **Ella** | E9–E11 | La prisionera en el agujero negro. Eli conecta. |
| **Camino** | E12–E13 | Liberación. La Estructura. La tripulación despierta. |

### Temporada 3: *El Origen*
*La Estructura Original. Los tres universos. El sacrificio. La amenaza que viene.*

| Bloque | Episodios | Descripción |
|--------|-----------|-------------|
| **Los Dormidos** | E1–E4 | La tripulación original despierta. Choque cultural. |
| **Revelación** | E5–E8 | Los tres universos. El código está agotado. Alguien debe sacrificarse. |
| **Sacrificio** | E9–E11 | Eli recibe el código. Batalla. **Hawkins cae.** |
| **Código Fuente** | E12–E13 | Eli cruza a la Estructura. El ciclo se completa. **Algo llega desde la oscuridad.** |

---

## 🤝 Cómo contribuir

Este proyecto es **abierto a la comunidad**. No importa si eres guionista, artista 3D, científico o fan — hay un lugar para ti.

### 🖊️ Como escritor

Los guiones están en `series/season-XX/episode-XX/screenplay.md` con formato profesional. Puedes:

- **Revisar y editar** guiones existentes — ¿un diálogo no funciona? Abre un PR.
- **Escribir episodios de relleno** — aventuras autónomas que desarrollen personajes o exploren el universo.
- **Proponer variaciones** — ¿y si el final fuera diferente? Los "what if" son bienvenidos.
- **Corregir lore** — ¿algo contradice el canon de Stargate? Avísanos.

**Formato de guión:**
```screenplay
**INT. DESTINY - SALA DE COMPUERTAS - DÍA**

La compuerta se activa. El vórtice azul se estabiliza.

ELI
(susurrando a Wilson)
Aquí vamos.

CARTER
(cruzando el portal)
Eli. ¿Eres tú?
```

### 🎨 Como artista 3D (Blender)

La serie está diseñada para **producción hiperrealista en Blender**. Cada escena incluye notas `[BLENDER]` con especificaciones de cámara, iluminación y VFX.

- Consulta `blender/assets.md` para la lista de assets necesarios.
- Modela personajes, naves, sets y props.
- Crea materiales procedurales, texturas y shaders.
- Propón planes de iluminación y cinematografía.

### 🔬 Como asesor científico

La serie se toma la ciencia en serio. Si tienes formación en física, cosmología o matemáticas:

- Revisa las explicaciones del código fuente, FTL y fenómenos cósmicos.
- Sugiere mejoras para que la ciencia ficción sea más creíble.
- Ayuda a desarrollar el "lenguaje" del código fuente.

### 🗣️ Como fan

- **Feedback narrativo**: ¿un personaje no funciona? ¿un arco se siente forzado?
- **Teorías**: ¿quién es la figura del cristal del post-créditos?
- **Discusión general**: usa GitHub Discussions para teorizar y debatir.

### 🚀 Cómo empezar

1. **Haz fork** del repositorio.
2. **Elige una rama** o crea una nueva para tu contribución.
3. **Lee los archivos** de la `00-bible/` para entender el lore y los personajes.
4. **Abre un issue** para discutir cambios grandes antes de enviar un PR.
5. **Envía tu PR** con una descripción clara.

---

## 📁 Estructura del repositorio

```
├── series/
│   ├── 00-bible/               # Documentación base
│   │   ├── logline.md          # Concepto central
│   │   ├── timeline.md         # Cronología completa
│   │   ├── world-building.md   # Universo, facciones, tecnología
│   │   └── personajes/         # Fichas de personajes con arcos
│   ├── season-01/              # Temporada 1: "El Despertar"
│   ├── season-02/              # Temporada 2: "El Mapa"
│   └── season-03/              # Temporada 3: "El Origen"
│       └── episode-XX/
│           └── screenplay.md   # Guión completo con diálogo
│
├── blender/
│   ├── assets.md               # Lista maestra de assets a modelar
│   ├── shots-list.md           # Lista de planos por episodio
│   └── render-queue.md         # Plan de renderizado
│
└── .opencode/
    └── skills/                 # Workflow de escritura con opencode
```

Cada episodio incluye:
- **`screenplay.md`** — Guión completo con diálogo, acción y notas de producción `[BLENDER]`.

---

## 🎬 Producción en Blender

Todo el contenido está escrito para ser **producible en Blender** con estándares hiperrealistas. Los guiones incluyen notas técnicas integradas:

```screenplay
[BLENDER]
CAMERA: Dolly lento, focal 35mm, f/2.8, DOF en rostro de Eli
LIGHTS: Luz práctica desde panel de control (naranja, 3200K)
        Relleno frío desde compuerta (azul, 5600K)
MATERIALS: Piel con subsurface scattering
           Metal desgastado con noise texture procedural
VFX: Partículas de polvo en suspensión (sistema de partículas)
```

---

## 📊 Estado actual

| Componente | Progreso |
|-----------|----------|
| Bible (lore, personajes, timeline) | ✅ 100% |
| Temporada 1 — Guiones | ✅ 100% (7,733 líneas) |
| Temporada 2 — Guiones | ✅ 100% (8,619 líneas) |
| Temporada 3 — Guiones | ✅ 100% (5,199 líneas) |
| Plan de assets Blender | 🔄 Pendiente |
| Cinematografía por episodio | 🔄 Pendiente |
| Modelado 3D | ⏳ No iniciado |

---

## ⚠️ Aviso legal

Este es un proyecto **fan no oficial**. *Stargate* es propiedad de MGM. Este trabajo es sin ánimo de lucro, creado por y para la comunidad.

---

<p align="center">
<i>Ocho años. Ocho años hablando solo, reparando esta nave, manteniendo viva a gente que ni siquiera sabe que estoy aquí.</i><br>
— Eli Wallace
</p>

<p align="center">
  <a href="https://github.com/lucasmanoguerra/blender-stargate-series/issues">Reportar un issue</a> •
  <a href="https://github.com/lucasmanoguerra/blender-stargate-series/discussions">Discusiones</a> •
  <a href="https://github.com/lucasmanoguerra/blender-stargate-series/pulls">Enviar un PR</a>
</p>
