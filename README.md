# Stargate: Destiny

Serie cinematográfica hiperrealista creada íntegramente en Blender.

Continuación directa de Stargate Universe (+2 años Tierra / +10 años Destiny).

## Premisa

La Tierra establece una conexión interestelar permanente con la nave perdida Destiny. Eli Wallace sigue vivo. Pero la nave ha cruzado galaxias siguiendo un patrón imposible — migas de pan dejadas por las naves sembradoras — hacia el origen del universo. Una civilización más antigua que los Antiguos, Los Curadores, lleva eones eliminando a quienes se acercan demasiado al secreto del código fuente cosmológico.

## Estructura del proyecto

```
series/
├── 00-bible/           # Documentación base de la serie
│   ├── logline.md
│   ├── world-building.md
│   ├── timeline.md
│   └── personajes/     # Fichas de personajes
├── season-01/          # Temporada 1 (13 episodios)
│   └── episode-01/     # Piloto: "El Último Salto"
│       ├── screenplay.md      # Guión completo con diálogo
│       ├── escenas.md         # Desglose de producción
│       ├── cinematografia.md  # Plan de cámara y luces
│       └── beat-sheet.md      # Estructura por actos
└── blender/            # Plan de producción técnica
    └── assets.md       # Lista de assets para modelado
```

## Herramientas

- **Skill opencode**: `screenplay-structurer` — workflow de guión profesional
- **Render**: Blender Cycles / Eevee
- **Formato**: Guión técnico con notas de producción integradas
