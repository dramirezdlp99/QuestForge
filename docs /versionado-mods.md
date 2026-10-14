# Versionado de mods en QuestForge

## ¿Qué es el versionado?

El versionado es una forma ordenada de numerar las versiones de un mod. Cada vez que el mod cambia, se le asigna un nuevo número para saber qué cambió y cuándo.

En QuestForge se usa el formato **MAJOR.MINOR.PATCH**, por ejemplo `v1.2.3`:

| Parte | Cuándo aumenta | Ejemplo |
|-------|----------------|---------|
| **MAJOR** | Cambios grandes que pueden romper la compatibilidad | `v1.4.2 → v2.0.0` |
| **MINOR** | Se agregan funciones o contenido nuevo sin romper lo anterior | `v1.0.0 → v1.1.0` |
| **PATCH** | Se corrigen errores pequeños | `v1.1.0 → v1.1.1` |

## ¿Por qué sirve?

- **Claridad:** los jugadores saben qué versión del mod usan.
- **Compatibilidad:** permite saber si un mod funciona con el juego o con otros mods.
- **Orden:** el equipo habla siempre de la misma versión y evita confusiones.

## Ejemplo de cambio entre versiones: `v1.0.0 → v1.1.0`

Imaginemos un mod llamado **"Espadas Élficas"**:

- **v1.0.0:** primera versión publicada, con 3 espadas nuevas.
- **v1.1.0:** se agregan 2 espadas más y una misión asociada.

Se añadió contenido nuevo sin romper lo que ya existía, por eso solo sube el número **MINOR**. Quien tenía la v1.0.0 puede actualizar sin problemas.

## ¿Qué cambios se registrarían?

En cada versión se debe dejar constancia de:

- **Nuevas funciones o contenido** (nuevos objetos, misiones, personajes).
- **Correcciones de errores** (fallos que se arreglaron).
- **Cambios en funciones existentes** (ajustes de balance, cambios de comportamiento).
- **Cambios que rompen compatibilidad** (algo que obliga a actualizar otros mods o partidas guardadas).
- **Elementos eliminados** (contenido que ya no está disponible).
- **Fecha de publicación** y **autor** del cambio.

Ejemplo de registro:

```
v1.1.0 - 2026-10-14
- Agregadas 2 espadas nuevas.
- Agregada misión "El bosque antiguo".
```

## ¿Por qué es útil conservar el historial?

1. **Permite volver atrás:** si una versión nueva falla, se puede recuperar la anterior.
2. **Ayuda a encontrar errores:** se puede ver en qué versión apareció un problema.
3. **Da transparencia:** los jugadores saben qué trae cada actualización.
4. **Facilita el trabajo en equipo:** cada persona sabe qué se hizo antes y por quién.
5. **Protege el trabajo:** nada se pierde aunque el mod cambie muchas veces.
