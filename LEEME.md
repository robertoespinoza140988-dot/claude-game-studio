# Claude Game Studio (Roberto)

Copia del estudio de juegos [Donchitos/Claude-Code-Game-Studios](https://github.com/Donchitos/Claude-Code-Game-Studios) (licencia MIT): 49 agentes y 78 comandos para Claude Code que diseñan, construyen y revisan juegos.

## Cómo usarlo

1. Abre Claude Code en la nube (claude.ai/code) y elige el repo **claude-game-studio**.
2. Escribe uno de estos comandos:

| Comando | Qué hace |
|---|---|
| `/prototype un juego de ...` | Te hace unas preguntas, escribe la ficha del juego y construye un juego de navegador jugable |
| `/prototype --from <ruta>` | Trae un juego HTML que ya tengas para mejorarlo |
| `/help` | Muestra qué puedes hacer según en qué etapa vas |
| `/balance-check` | Revisa el balance y la dificultad |
| `/code-review` | Revisión del código |
| `/qa-plan` | Plan de pruebas |
| `/playtest-report` | Informe de prueba de juego |
| `/launch-checklist` | Lista de verificación antes de publicar |

Los juegos nuevos quedan en `prototypes/<nombre>/` y se abren con doble clic.

## Los otros 4 repos del video

No corren en la nube porque necesitan tu PC:

- **UnrealClaude**: plugin para Unreal Engine 5.7.
- **godot-mcp**: necesita Godot instalado.
- **ACE-Step 1.5** (música): necesita tarjeta gráfica. Hay una versión web gratis en acemusic.ai.
- **Audio2Face-3D** (NVIDIA): necesita GPU NVIDIA y Unreal Engine 5.
