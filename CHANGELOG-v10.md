# Panel de Riesgo de Jurisdicciones — v10

**Corte de datos: 13 de agosto de 2026** (la versión anterior, v9, tenía corte en febrero de 2026)

---

## 1. Vigencia por fuente

| Fuente | Vigente desde | Detalle | Próxima actualización |
|---|---|---|---|
| GAFI — listas negra y gris | 19-jun-2026 | Plenario del 17-19 de junio | Octubre 2026 |
| UE — terceros países alto riesgo PLD/FT | 29-ene-2026 | Regs. Delegados (UE) 2026/46 y 2026/83 | Sin fecha anunciada |
| UE — jurisdicciones no cooperativas (fiscal) | 17-feb-2026 | Conclusiones del Consejo ECOFIN | Octubre 2026 |
| Transparency International — CPI 2025 | 10-feb-2026 | 182 países | Ene-feb 2027 (est.) |
| IEP — Global Terrorism Index 2026 | 19-mar-2026 | 163 países, datos 2025 | Marzo 2027 (est.) |
| GI-TOC — Global Organized Crime Index 2025 | 10-nov-2025 | 193 países, ciclo bienal | 2027 (est.) |
| Sanciones OFAC / UE / ONU | Agosto 2026 | Programas por país | Revisión trimestral sugerida |

---

## 2. Cambios en listas regulatorias

### GAFI (19 de junio de 2026)

- **Altas a lista gris:** Bosnia y Herzegovina, Irak
- **Bajas de lista gris:** Argelia, Namibia
- **Lista negra sin cambios:** Corea del Norte, Irán, Myanmar
- **Rusia:** membresía suspendida (ahora puntúa como riesgo alto, antes no puntuaba)
- Total lista gris: 22 jurisdicciones

### UE — PLD/FT (29 de enero de 2026)

- **Altas:** Bolivia, Islas Vírgenes Británicas, Rusia
- **Bajas:** Burkina Faso, Malí, Mozambique, Nigeria, Sudáfrica, Tanzania
- La lista pasó de 29 a **26 jurisdicciones**
- Rusia entra bajo una categoría nueva del Anexo: miembro del GAFI con membresía suspendida

**Divergencia crítica UE ↔ GAFI.** La UE no ha transpuesto los plenarios del GAFI de febrero ni de junio de 2026:

| Situación | Jurisdicciones | Consecuencia |
|---|---|---|
| Fuera del GAFI, dentro de la UE | Argelia, Namibia, Afganistán, Trinidad y Tobago, Vanuatu | La DDR sigue siendo **obligatoria** en la UE |
| Dentro del GAFI, fuera de la UE | Bosnia y Herzegovina, Irak, Bulgaria, Kuwait, Papúa Nueva Guinea | Solo alimenta la evaluación interna de riesgo |

Las obligaciones del artículo 18 bis de la Directiva (UE) 2015/849 se activan **solo** por la lista de la UE.

### UE — Fiscal (17 de febrero de 2026)

- **Anexo I (10):** Samoa Americana, Anguila, Guam, Palaos, Panamá, Rusia, **Islas Turcas y Caicos (nueva)**, Islas Vírgenes de EE.UU., Vanuatu, **Vietnam (nuevo, elevado desde el Anexo II)**
- **Bajas del Anexo I:** Fiyi, Samoa, Trinidad y Tobago
- **Anexo II (9):** Belice, Islas Vírgenes Británicas, Brunéi, Esuatini, **Groenlandia**, **Jordania**, **Montenegro**, **Marruecos**, Turquía
- **Bajas del Anexo II:** Antigua y Barbuda, Seychelles

Se corrigió además la etiqueta inconsistente "Lista Negra Fiscal UE" que la v9 usaba para Costa Rica, Panamá y Rusia. Costa Rica ya no figura en ninguna lista fiscal de la UE.

---

## 3. Índices recalibrados

- **CPI 2025** aplicado a los 182 países cubiertos por Transparency International. La v9 solo tenía 70 países actualizados.
- **GTI 2026** sustituye al GTI 2025. Pakistán ocupa el puesto 1 por primera vez. Movimientos relevantes: Colombia 15→9, Ecuador 56→37, Australia 46→31, Estados Unidos 34→28.
- **OC Index 2025** (criminality score verificado, 193 países) sustituye las puntuaciones anteriores, que en varios casos no correspondían a ninguna edición publicada. Se eliminó el campo duplicado "Puntaje General / Nivel de Criminalidad": el OC Index publica un solo criminality score.

Ejemplos de corrección: Estados Unidos 6.35 → **5.87**; Afganistán 7.83 → **7.02**; México 7.0 aprox. → **7.68 (#3 mundial)**.

---

## 4. Nueva dimensión: sanciones internacionales

Se incorporó un sexto eje al modelo 360Score, con tres niveles:

| Nivel | Puntúa | Jurisdicciones |
|---|---|---|
| **Integrales** (embargo territorial) | 5 — hard stop | Cuba, Irán, Corea del Norte |
| **Amplias / Sectoriales** | 4 | Rusia, Bielorrusia, Venezuela, Myanmar, Afganistán, Nicaragua, Siria, China (parcial), Hong Kong |
| **Dirigidas (ONU/UE)** | 3 | 22 jurisdicciones con Comité de Sanciones de la ONU o régimen geográfico de la UE |

Cambios de fondo detectados en 2026:

- **Cuba se endureció de forma decisiva.** La Orden Ejecutiva 14404 (1-may-2026) creó un programa bajo IEEPA con **sanciones secundarias a instituciones financieras extranjeras**. Es la primera vez que un sujeto obligado mexicano puede quedar expuesto por operaciones cubanas sin nexo con el sistema financiero estadounidense. Requiere atención específica en la política interna.
- **Siria se relajó.** OFAC archivó el programa integral y lo sustituyó por PAARSS, de alcance dirigido; el Caesar Act fue derogado en diciembre de 2025; la rescisión de la designación como Estado Patrocinador del Terrorismo se inició el 8 de julio de 2026 y **aún no está consumada**.
- **Venezuela se relajó parcialmente.** Licencias generales amplias tras la salida de Maduro, sin revocación de ninguna Orden Ejecutiva.
- **Irán se agravó a nivel ONU.** El snapback de septiembre de 2025 reactivó las resoluciones 1737/1747/1803/1929.
- **Zimbabue prácticamente salió.** La UE levantó viajes y congelamientos el 17-feb-2026; solo persiste el embargo de armas.

### Etiquetas del 360Score

Se separó el hard stop en dos categorías, porque no son lo mismo para un sujeto obligado mexicano:

- **PROHIBIDO** — lista negra del GAFI (Corea del Norte, Irán, Myanmar). Obligación regulatoria directa.
- **BLOQUEO POR SANCIONES** — embargo integral sin lista negra del GAFI (Cuba). Prohibición de facto por exposición extraterritorial, no por norma mexicana. Requiere validación jurídica caso por caso.

---

## 5. Cobertura ampliada

Se agregaron **7 jurisdicciones** que faltaban pese a figurar en listas vigentes o regímenes de sanciones: Vanuatu, Samoa Americana, Guam, Islas Turcas y Caicos, Groenlandia, Túnez y Corea del Sur. Se eliminó un registro duplicado (Guinea Ecuatorial).

**Total: 187 jurisdicciones** (antes 181).

---

## 6. Distribución resultante del 360Score

| Nivel | Jurisdicciones |
|---|---|
| 5 · PROHIBIDO | 3 |
| 5 · BLOQUEO POR SANCIONES | 1 |
| 5 · Riesgo Extremo | 13 |
| 4 · Riesgo Alto | 44 |
| 3 · Riesgo Elevado | 55 |
| 2 · Riesgo Moderado | 45 |
| 1 · Riesgo Bajo | 26 |

---

## 7. Verificación realizada

- Conteos cruzados contra fuentes primarias: GAFI 3 + 22 + 1 suspendida ✓ · UE PLD/FT 26 ✓ · UE fiscal 10 + 9 ✓
- Renderizado sin errores de consola ni de React (Chromium/Playwright)
- Sin duplicados, sin campos vacíos, 187 registros íntegros

## 8. Pendiente de vigilancia

- Un nuevo reglamento delegado de la UE que transponga los plenarios del GAFI de 2026 (probable, sin fecha)
- Revisión de la lista fiscal de la UE en octubre de 2026 — vencieron los plazos de Panamá (17-jul), Anguila (24-jul) y Brunéi (30-jun); Montenegro vence el 15-ago
- Consumación de la rescisión SST de Siria (~22-ago-2026)
- Plenario del GAFI de octubre de 2026
