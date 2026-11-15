# Panel de Riesgo de Jurisdicciones — v11

**Corte de datos: 15 de noviembre de 2026** (la versión anterior, v10, tenía corte el 13 de agosto de 2026)

## 1. Vigencia por fuente

| Fuente | Vigente desde | Detalle | Próxima actualización |
|---|---|---|---|
| GAFI — listas negra y gris | 30-oct-2026 | Plenario de octubre de 2026 | Febrero 2027 |
| UE — terceros países alto riesgo PLD/FT | 29-ene-2026 | Regs. Delegados (UE) 2026/46 y 2026/83 (sin acto posterior identificado) | Sin fecha anunciada |
| UE — jurisdicciones no cooperativas (fiscal) | 09-oct-2026 | Conclusiones del Consejo, doc. 13854/26 | Febrero 2027 (est.) |
| CPI 2025 · GTI 2026 · OC Index 2025 | Sin cambio | Ediciones vigentes | Sin cambio |

## 2. Cambios en datos

| Jurisdicción | Cambio | Fuente | Puntaje |
|---|---|---|---|
| Bulgaria | Sale de la lista gris del GAFI | GAFI, 30-oct-2026 | 4 → 3 |
| Costa de Marfil | Sale de la lista gris del GAFI; sigue en lista UE PLD/FT | GAFI, 30-oct-2026 | 4 → 3 |
| República Democrática del Congo | Sale de la lista gris del GAFI; sigue en lista UE PLD/FT y sanciones dirigidas | GAFI, 30-oct-2026 | 4 → 4 |
| Mónaco | Sale de la lista gris del GAFI; sigue en lista UE PLD/FT y REFIPRES | GAFI, 30-oct-2026 | 4 → 3 |
| Panamá | UE fiscal: Anexo I → Anexo II | Consejo, 09-oct-2026 | 3 → 3 |
| Vietnam | UE fiscal: Anexo I → Anexo II; advertencia del GAFI sobre su ritmo de avance | Consejo, 09-oct-2026; GAFI, 30-oct-2026 | 4 → 4 |
| Belice | Sale del Anexo II de la UE; conserva REFIPRES | Consejo, 09-oct-2026 | 3 → 3 |
| Brunéi, Montenegro | Notas del Anexo II actualizadas | Consejo, 09-oct-2026 | Sin cambio |
| Irán, Corea del Norte | Campo nuevo `gafiMedida`: Contramedidas | GAFI, 30-oct-2026 | Sin cambio |
| Myanmar | `gafiMedida`: debida diligencia reforzada (no contramedidas) | GAFI, 30-oct-2026 | 5 → 5 |
| Baréin | Texto: se elimina la mención falsa a la lista gris | GAFI, feb-2026 | Sin cambio |
| Brasil | Texto alineado a OC Index 7.07 y CPI 35 | ocindex.net; transparency.org | Sin cambio |
| Nicaragua | Texto alineado a CPI 14 | transparency.org | Sin cambio |

Conteos resultantes: lista gris GAFI 18 · lista negra 3 · UE PLD/FT 26 · UE Anexo I 8 · Anexo II 10.

## 3. Etiqueta del 360Score (autorizada por Maribel Vázquez, 15-nov-2026)

- **PROHIBIDO**: sólo lista negra del GAFI con llamado a contramedidas (Irán, Corea del Norte).
- **LISTA NEGRA GAFI · DDR REFORZADA** (nueva): lista negra cuando el GAFI pide debida diligencia reforzada y no contramedidas (Myanmar). Acción: «Obligación en México: conforme a DCG/UIF».
- La fórmula, los pesos y los umbrales **no cambian**.

## 4. Distribución resultante

| Nivel | v10 | v11 |
|---|---|---|
| 5 · PROHIBIDO | 3 | 2 |
| 5 · Lista negra GAFI · DDR reforzada | — | 1 |
| 5 · BLOQUEO POR SANCIONES | 1 | 1 |
| 5 · Riesgo Extremo | 13 | 13 |
| 4 · Riesgo Alto | 44 | 41 |
| 3 · Riesgo Elevado | 55 | 58 |
| 2 · Riesgo Moderado | 45 | 45 |
| 1 · Riesgo Bajo | 26 | 26 |

## 5. Verificación

- Diff registro por registro contra v10: 15 registros tocados, todos los listados arriba; 187 registros íntegros.
- Renderizado sin errores de consola en Chrome, en computadora (1366 px) y celular (390 px).
