# ghcp-lab-1900

Proyecto mínimo para el laboratorio guiado de **GitHub Copilot Business** en VS Code,
acotado a un presupuesto de **1,900 AI Credits** por usuario/mes.

## Qué hay aquí

| Archivo | Rol en el laboratorio |
|---|---|
| `src/inventory.js` | Estilo consistente y documentado. Base para **autocompletado** (0 créditos). |
| `src/pricing.js` | Código heredado sin nombres, sin validación, sin docs, sin pruebas. Base para **explicación, documentación, pruebas y refactor**. |
| `src/tarifas.js` | Tablas de referencia (impuestos y tipo de cambio). |
| `src/server.js` | API HTTP mínima. Base para **nuevo requerimiento** y **automatización**. |
| `tests/` | Vacío a propósito. Cobertura inicial = 0 %. |
| `.vscode/settings.json` | Palancas de control de consumo de créditos. |

## Puesta en marcha

```bash
npm install
npm test          # 0 pruebas: ese es el punto de partida
npm start         # http://localhost:3000/health
```

## Reglas del laboratorio

1. **Máximo valor demostrado.**
2. **Techo duro: 1,900 AI Credits.** El diseño apunta a consumir ~600–700.

No edites este README durante la sesión. Los prompts los entrega el presentador.
