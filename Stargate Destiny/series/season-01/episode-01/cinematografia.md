# Plan de Cinematografía — Episodio 1: "El Último Salto"

---

## CO-01: "Día 4387" — Destiny Puente

### Toma 1.1 — Establecimiento

- **Tipo de plano**: Extreme Wide
- **Movimiento**: Dolly out lento
- **Duración**: 10s
- **Descripción**: El puente en penumbra. Eli sentado, pequeño, solitario.

```
[CAMERA]
- Focal length: 35mm
- Sensor: Full Frame
- Aperture: f/2.8
- DOF: Off
- Res: 3840x2160 (4K)
- FPS: 24
- Render: Cycles
```

```
[LIGHTS]
- Key: None (oscuridad base)
- Ambient: Solo luces de emergencia (point lights ámbar, 1W, 1800K)
- Accent: Monitor iluminando rostro de Eli (area light azul, 5W, 6500K)
```

### Toma 1.2 — Primer plano de Eli

- **Tipo de plano**: Close-up
- **Movimiento**: Estática, ligero push in
- **Duración**: 15s
- **Descripción**: Eli habla. Cansado. Grave.

```
[CAMERA]
- Focal length: 85mm
- Sensor: Full Frame
- Aperture: f/1.4
- DOF: On (focus: ojos Eli)
- Res: 3840x2160
```

```
[LIGHTS]
- Key: Monitor (area light, fría, desde abajo)
- Fill: Ninguno (deseado: sombras duras)
- Mood: Cansancio, derrota
```

### Toma 1.3 — Giro

- **Tipo de plano**: Medium shot
- **Movimiento**: Whip pan hacia panel que se enciende
- **Duración**: 5s
- **Descripción**: Los sistemas se activan. Luz azul irrumpe.

```
[CAMERA]
- Focal length: 50mm (pan rápido)
```

```
[LIGHTS]
- Nuevo: Azul brillante (6500K) desde panel. Contraste ámbar/azul.
```

---

## CO-02: "Reactivación" — Corredor

### Toma 2.1 — Tracking lateral

- **Tipo de plano**: Medium wide
- **Movimiento**: Tracking lateral, cámara paralela a Eli
- **Duración**: 30s
- **Descripción**: Eli camina, luces se encienden en cascada.

```
[CAMERA]
- Focal length: 40mm
- Sensor: S35
- Movimiento: Steadycam tracking
- Render: Eevee (para luces dinámicas en tiempo real)
```

```
[LIGHTS]
- Cascade effect: Luces empotradas se encienden en secuencia
- Intensidad progresiva (de 0 a 100%)
- Temperatura: 4500K (neutro cálido)
```

---

## CO-03: "La Llegada" — Sala de Compuertas

### Toma 3.1 — Plano amplio

- **Tipo de plano**: Wide
- **Movimiento**: Estática
- **Duración**: 10s

```
[CAMERA]
- Focal length: 24mm
- Aperture: f/8 (todo en foco para escala)
- Render: Cycles
```

```
[VFX]
- Stargate: Partículas del vórtice (azul/blanco)
- Chevrons: Bloqueo individual con luz
- Polvo: Particle system en toda la sala
```

---

## E01: "47 Segundos" — Sala de Control SGC

### Toma 4.1 — Plano general

- **Tipo de plano**: Wide
- **Movimiento**: Crane shot descendente
- **Duración**: 8s

```
[CAMERA]
- Focal length: 35mm
- Sensor: Full Frame
```

```
[LIGHTS]
- Key: Tech lighting (area lights empotradas, 5500K, frío)
- Pantallas: Azul, con emisión
- Ambiente: Limpio, tecnológico, contrasta con la Destiny
```

### Toma 4.2 — McKay y Carter

- **Tipo de plano**: Over-shoulder, dos shots
- **Movimiento**: Estática

```
[CAMERA]
- Focal length: 70mm
- DOF: On
```

---

## E06: "Eli" — Primer Encuentro

### Toma 6.1 — La entrada de Eli

- **Tipo de plano**: Medium wide
- **Movimiento**: Slow dolly in
- **Duración**: 15s
- **Descripción**: Eli emerge de la oscuridad hacia el haz de luz. **Toma icónica del episodio.**

```
[CAMERA]
- Focal length: 50mm
- Aperture: f/2.0
- DOF: On (transición: oscuridad → luz)
- Res: 3840x2160
```

```
[LIGHTS]
- Backlight: Stargate (area light azul intensa, 100W, 6500K) desde la compuerta
- Fill lateral: Ninguno (deseado: silueta parcial)
- Ambiente: Oscuridad total excepto haz

[COMPOSITION]
- Eli camina hacia cámara, ligeramente descentrado
- El haz de luz forma un cono visible (partículas de polvo)
- Silueta al inicio → detalles al acercarse
```

### Toma 6.2 — Close-up emocional

- **Tipo de plano**: Extreme Close-up (ojos de Eli)
- **Duración**: 5s
- **Descripción**: Los ojos de Eli. Han visto 10 años de soledad.

```
[CAMERA]
- Focal length: 135mm
- Aperture: f/1.2
- DOF: Extremadamente superficial
```

```
[MATERIALS]
- Piel: Subsurface scattering alto (piel desgastada)
- Textura: Poros, arrugas prematuras, ojeras profundas
```

---

## E08: "El Tour" — Destiny Interiores

### Toma 8.1 — Montaje de pasillos

- **Tipo de plano**: Tracking forward
- **Movimiento**: Dolly-in a través de la nave, siguiendo a Eli
- **Duración**: 60s (montaje, cortes rápidos)

```
[CAMERA]
- Focal length: 28mm
- Render: Eevee (rapidez de render)
- Estilo: Semi-documental, ligero handheld
```

```
[LIGHTS]
- Pasillos: Luces empotradas anaranjadas (3000K)
- Zonas muertas: Penumbra total
- Transiciones: Luz→sombra→luz
```

### Toma 8.2 — La pared de días

- **Tipo de plano**: Dolly lateral lento
- **Duración**: 10s
- **Descripción**: La pared cubierta de marcas. Miles.

```
[CAMERA]
- Focal length: 35mm
- Movimiento: Lento, horizontal
- Foco: En las marcas, desenfoque de fondo
```

```
[VFX]
- Marcas: Geometry nodes con instancias de rayas
- Variedad: Algunas más profundas (años), otras superficiales
```

---

## E13: "El Análisis" — Briefing SGC

### Toma 13.1 — La revelación

- **Tipo de plano**: Medium group
- **Movimiento**: Estática, luego push-in a Daniel
- **Duración**: 30s

```
[CAMERA]
- Focal length: 50mm → 85mm (push-in lento)
- DOF: On (fondo desenfocado, foco en Daniel)
```

```
[LIGHTS]
- Key: Overhead con gel azul (misterio)
- Holograma: Proyección central como fuente de luz principal
- Rostro de Daniel: Iluminado por el patrón desde abajo
- Shadows: Duras, dramáticas

[COMPOSITION]
- Daniel en el centro de la composición
- Patrón holográfico flotando sobre la mesa
- Los demás en penumbra alrededor
```

### Toma 13.2 — La reacción

- **Tipo de plano**: Close-up de Carter
- **Duración**: 5s
- **Descripción**: Carter procesa las palabras de Daniel.

```
[CAMERA]
- Focal length: 100mm
- Aperture: f/2.0
```

---

## E15: "La Estructura" (Cliffhanger)

### Toma 15.1 — Flash fugaz

- **Tipo de plano**: Extreme Wide
- **Movimiento**: Orbit virtual (cámara alrededor de la Estructura)
- **Duración**: 15s

```
[CAMERA]
- Focal length: 14mm (ultra wide)
- Sensor: Full Frame
- Res: 3840x2160
- Render: Cycles (máxima calidad)
```

```
[LIGHTS]
- Fuente principal: La Estructura misma (emissive)
- Colores: Violeta, verde esmeralda, negro profundo
- Partículas: Energía fluyendo alrededor

[VFX]
- Nebulosa de fondo con movimiento lento
- Distorsión del espacio alrededor de la Estructura
- Efecto de lente (lens flare sutiles)
- Particulas de luz ascendiendo

[COMPOSITION]
- Regla de tercios: Estructura en tercio superior
- Leading lines: Tentáculos de materia hacia la Estructura
- Color: Cool tones (violeta/negro) con acentos verdes
```

---

## Resumen de planos por escena

| Escena | Planos | Dificultad | Complejidad |
|--------|--------|------------|-------------|
| CO-01 | 3 | Compleja | Iluminación dramática, personaje con SS |
| CO-02 | 1 | Media | Luces en cascada, tracking |
| CO-03 | 1 | Compleja | Stargate con partículas, polvo |
| E01 | 2 | Media | Set SGC con hologramas |
| E02 | 2 | Media | Briefing con proyección 3D |
| E03 | 1 | Media | ZPM con emisión azul |
| E04 | 2 | Heroica | Supergate, escala masiva, partículas |
| E05 | 1 | Media | Sala vacía, atmósfera |
| E06 | 2 | Compleja | Eli, iluminación dramática, momento clave |
| E07 | 2 | Media | Split screen, contraste frío/calor |
| E08 | 3 | Compleja | Montaje, tracking, múltiples sets |
| E09 | 2 | Media | Iluminación íntima, props detallados |
| E10 | 2 | Compleja | Holograma 3D del mapa galáctico |
| E11 | 1 | Compleja | Patrón geométrico imposible |
| E12 | 1 | Media | Efectos de estática, interrupción |
| E13 | 3 | Media | Briefing, iluminación dramática |
| E14 | 1 | Media | Eli solo, reflexión en cristal |
| E15 | 1 | Heroica | Cliffhanger: megaestructura CGI completa |

---

## Prioridades de render

| Prioridad | Escena | Razón |
|-----------|--------|-------|
| **Crítica** | E06 (entrada de Eli) | Momento icónico del episodio. Iluminación compleja. |
| **Crítica** | E15 (Estructura) | Cliffhanger. Debe impactar. Render Cycles. |
| **Alta** | CO-01, CO-03 | Cold open. Define el tono. |
| **Alta** | E10, E11 (mapa/patrón) | Primer vistazo al misterio central. |
| **Media** | E01-E04 (SGC) | Sets interiores, más controlables. |
| **Media** | E08-E09 (Tour Destiny) | Sets extensos pero repetibles. |
| **Baja** | Escenas de diálogo | Planos cerrados, fondo controlado. |
