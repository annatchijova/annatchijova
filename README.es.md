# Anna Tchijova

[English](README.md) · **Español** · [LinkedIn](https://www.linkedin.com/in/anna-tchijova/)

Hola, soy Anna Tchijova. Nací en Rusia y vivo en Argentina. Soy fanática de la F1 —específicamente de McLaren y de Alain Prost—, sensocentrista y practico el altruismo eficaz. ¡Y ahora construyo sistemas! La gran mayoría con licencia Apache 2.0 o MIT.

Una de mis pasiones siempre fue la investigación; otra, la gastronomía de autor, donde me desarrollé profesionalmente. La cocina me enseñó a trabajar con *seguridad primero*: disminuir errores, mantener trazabilidad, reducir riesgos, atender muchos procesos a la vez y optimizar el tiempo. Llegan diez comandas y necesitás un equipo coordinado haciendo bien las cosas, porque todo depende de todo y un pequeño error puede terminar en un plato mal hecho o en una intoxicación.

Toda la vida leí mucho, muchísimo, y siempre tuve buenas ideas, pero no era programadora. Eso cambió con los LLM: te ayudan con la sintaxis, pero no reemplazan el criterio humano. Son como buenos colegas que también pueden equivocarse. Mi primer trabajo lo hice con siete LLM distintos desde la web, poniéndolos a debatir por turnos —debates infinitos— para entender sus alineamientos y sesgos. Después descubrí las CLI y pasé a trabajar de forma híbrida: múltiples terminales y agentes, más algunos que seguían en la web.

No quiero un equipo que me diga que todo está bien, y eso se ve en mis 92 skills, creadas con la metodología que aprendí en años de Ciencias Sociales, investigación, lógica, filosofía, semiótica y epistemología. No necesito resultados rápidos, inmediatos, descartables ni inseguros. Prefiero una metodología que me permita construir de forma coherente, por capas, sin dejar bugs sueltos "para después".

Además de investigar temas de derechos humanos y derechos no humanos, soy investigadora independiente en seguridad e inteligencia artificial: investigación de vulnerabilidades, DFIR, sistemas agénticos, OSINT/HUMINT y arquitecturas de seguridad verificables.

Hice muchos jailbreaks epistemológicos a LLM con un único objetivo: que lo que construyo sea seguro. No los publiqué —ni los prompts ni, menos todavía, las respuestas—; es parte de mi ética. No tengo un "ego hacker" que proteger. Encontrar bugs en mis propios sistemas es una oportunidad: a las matemáticas no les importa el ego.

**Me encantaría que le hagan red team a mis sistemas, y doy mi consentimiento explícito para hacerlo.**

Tengo más de 15 años de experiencia en investigación multidisciplinaria, perfilamiento y conducta: prestar atención a qué se dice, cómo, cuándo, dónde, por qué y para qué. Estudio el comportamiento humano desde los 8 años, el de los LLM desde 2023, y reporto vulnerabilidades de seguridad desde 2025. Desde la niñez me interesan la investigación forense, la criptografía, la física, la inteligencia y la contrainteligencia, OSINT, HUMINT y SIGINT.

---

## Método

Mi método se basa en el método científico y la abducción peirceana: formulo explicaciones rivales para una observación, deduzco qué debería ocurrir si cada una fuera cierta y pongo a prueba esas predicciones con la intención de refutarlas. En investigación de seguridad, las hipótesis que fallan también son evidencia.

Conservo resultados negativos, documento las limitaciones conocidas y diseño pruebas sobre invariantes falsables, no demostraciones que solo confirman lo esperado. La reproducibilidad y la revisión adversarial son parte del resultado de investigación, no una tarea de limpieza posterior.

Por eso —jaja— cada repositorio mío tiene un `/docs` que puede llegar a tener decenas o cientos de documentos: ahí explico rondas de red team, por qué construyo lo que construyo, qué hice y qué falló, por qué tomé una decisión y no otra.

---

## Líneas de investigación

**Investigación de vulnerabilidades.** Investigo fallas en límites de confianza y autoridad: discrepancias de representación, confused deputy, SSRF, divergencias entre validación y acción, y fallas de composición. Mi trabajo incluye PoC ejecutables, análisis de variantes, divulgación coordinada y correcciones de seguridad integradas upstream. Cada auditoría termina en un reporte profesional que distingue lo auditado de lo no auditado, y los hallazgos confirmados de los falseados y los posibles.

**DFIR y sistemas deterministas.** Construyo sistemas forenses donde evidencia, inferencia y narración permanecen separadas, las decisiones son reproducibles y los modelos probabilísticos no adquieren autoridad sobre las conclusiones de manera silenciosa. En muchos casos me baso en el estándar Daubert.

**IA, agentes e ingeniería.** Investigo el comportamiento de modelos, el uso de herramientas, la autoridad de agentes, memoria y procedencia, evaluación adversarial, manipulación y autonomía acotada, especialmente cuando las decisiones automatizadas afectan a personas. En ingeniería trabajo con orquestación multiagente, diseño de harnesses, evaluación, pruebas y disciplina de ingeniería. Me siento cómoda orquestando y coordinando agentes, y construyendo harnesses.

**OSINT/HUMINT.** Mi formación en Ciencias Sociales y mi investigación en derechos humanos informan una práctica OSINT/HUMINT centrada en evaluar fuentes, contrastar hipótesis, corroborar, seguir contradicciones y procedencia, y explicitar la incertidumbre. Mi interés por la investigación forense, la inteligencia y la contrainteligencia empezó en la niñez y forma parte de la misma trayectoria.

---

## Proyectos destacados

### [VIGÍA](https://github.com/annatchijova/vigia-intent-analysis)

Formaliza el análisis de intención forense como un sistema determinista ejecutable. Combina razonamiento abductivo, análisis entre artefactos, incertidumbre y abstención explícitas, aritmética exacta para las decisiones, paquetes de evidencia sellados y autoauditoría adversarial. Amplía los Indicadores de Compromiso (IoC) con Indicadores de Intención (IoI) para analizar fracturas lógicas, contextuales y conductuales que pueden distinguir error, anomalía, acción deliberada, ocultamiento y manipulación. Los LLM pueden investigar o narrar; no controlan el veredicto.

### [JANUS](https://github.com/annatchijova/janus) · repositorio privado, en preparación para pymes

Simulador adversarial de ingeniería social que mide cómo las personas toman decisiones bajo incertidumbre contextual, no si hicieron clic. Trata la sobrerreacción y la credulidad como fallas simétricas, registra procesos de decisión ante casos benignos, maliciosos y ambiguos, y genera informes individuales y organizacionales.

### [ANNACONDA](https://github.com/annatchijova/annaconda)

Extiende la investigación forense a la adquisición en endpoints y flotas: recolección de evidencia acotada mediante Velociraptor y telemetría, ventanas de evidencia normalizadas, manifiestos y cadena de custodia. El sistema en vivo usa una flota de agentes Google ADK: los agentes investigan y delegan, mientras código determinista sella y adjudica la ventana antes de que un modelo la narre.

### [VELO](https://github.com/annatchijova/velo)

Atestación forense con conocimiento cero (ZK) sobre Midnight: el veredicto se ve, la evidencia permanece privada. Un motor determinista analiza evidencia local con aritmética racional exacta, gates de corroboración y cadena de custodia, más un paso obligatorio de Devil's Advocate antes de permitir un veredicto MALICE. Un circuito Compact prueba restricciones definidas sin revelar el caso. El flujo completo va del análisis local al bundle sellado, la prueba ZK, la atestación on-chain y la verificación independiente.

### [STYLOMETRY-CI](https://github.com/annatchijova/stylometry)

Gate de identidad forense para pipelines de GitLab. Siete núcleos forenses independientes comparan un commit con la línea de base conductual y estilística de la persona o el LLM que figura como autor —patrones de comportamiento, entropía, semiótica, cambios léxicos y de registro, cronobiología, atomicidad del commit y huellas sintácticas— y producen resultados deterministas PASS / WARN / REQUIRE_REVIEW / BLOCK con aritmética racional exacta.

### [PHYLO-Google](https://github.com/annatchijova/phylo-google) · código privado, disponible a pedido

La línea de PHYLO para la plataforma de Google. En este sistema evolutivo de optimización de código, el modelo propone mutaciones, sandboxes aislados (Pyodide/WASM y V8) ejecutan los candidatos, y pruebas y benchmarks seleccionan los cambios. Un Evolution Bundle firmado, verificable offline, registra la línea de base, las mutaciones, el candidato ganador y las mediciones.

### Criptografía aplicada: CONTINUUM · PROOF · VELO

Una línea de investigación sobre cómo los mecanismos criptográficos pueden hacer que decisiones, evidencia y estados sensibles sean verificables de forma independiente, sin exponer más información de la necesaria.

- **CONTINUUM** es un archivo de vida cifrado, local y recuperable: AES-256-GCM, cadenas de auditoría SHA-256, clasificación y recuperación deterministas, políticas de acceso y Shamir Secret Sharing para recuperación por umbral. La narración opcional con IA recibe solo evidencia ya seleccionada y no puede alterar el ranking, el acceso, la integridad ni las decisiones de liberación.
- **PROOF** verifica reclamos de pago contra el ledger de Stellar, en lugar de confiar en capturas de pantalla o datos declarados por quien paga. Reconstruye los hechos de la transacción, comprueba cada afirmación por separado, distingue VERIFIED / NOT VERIFIED / INSUFFICIENT EVIDENCE y sella el paquete con serialización canónica y SHA-256. Su verificador independiente detecta alteraciones posteriores; se ejercitó end-to-end en Stellar Testnet.
- **VELO** (arriba) lleva la misma idea a la atestación forense: solo un compromiso, el veredicto declarado y la prueba llegan a la cadena, y las restricciones del circuito impiden producir una atestación inválida esquivando los controles de la aplicación.

En conjunto exploran la verificabilidad sin divulgación innecesaria: custodia local cifrada, verificación de hechos en un ledger público y atestación forense con privacidad.

---

## Catálogo

Los repositorios agrupados por área. Los marcados como *privado* están disponibles a pedido o en desarrollo cerrado.

### Forense, DFIR y herramientas de investigación

- [**zaynor**](https://github.com/annatchijova/zaynor) — Plataforma DFIR local asistida por IA: normaliza y congela la evidencia antes del análisis determinista de VIGÍA; después permite explicar hallazgos sellados o ampliar la investigación con consultas de solo lectura por CLI, web, API y MCP.
- [**vigia**](https://github.com/annatchijova/vigia) — Centro del proyecto VIGÍA y materiales complementarios.
- [**vigia-cases**](https://github.com/annatchijova/vigia-cases) — Benchmark DFIR reproducible: material de casos y ground truth separados, mapeo MITRE ATT&CK, manifests SHA-256 y guía de scoring.
- [**forge**](https://github.com/annatchijova/forge) — Runtime local, de solo lectura, para auditorías reproducibles de repositorios: analizadores especializados con contratos explícitos, evidencia e hipótesis descartadas conservadas y hallazgos sellados para CLI, Python y MCP.
- [**forge-improved**](https://github.com/annatchijova/forge-improved) — Línea multilenguaje de Forge, con auditoría multiagente y abstención explícita cuando el alcance no permite sostener una conclusión.
- [**forge-results**](https://github.com/annatchijova/forge-results) — Manifests, benchmarks e informes por ejecución, separados del runtime para mantener atribución y reproducibilidad.
- [**orbit-guardian**](https://github.com/annatchijova/orbit-guardian) — Análisis de intención en merge requests: núcleos forenses independientes examinan payloads ofuscados, manipulación e ingeniería social, y exigen corroboración antes de presentar el resultado sellado a quienes revisan.
- [**pancito-red-team**](https://github.com/annatchijova/pancito-red-team) — Cada validación adversarial acotada vincula un cambio observable en el objetivo con una falla de control y con la telemetría defensiva que lo registra.
- [**moira**](https://github.com/annatchijova/moira) — Encuentra con aritmética racional exacta el corte causal mínimo de un historial determinista: qué transiciones se pueden quitar para cambiar el resultado.
- [**siberian**](https://github.com/annatchijova/siberian) — Modela el silencio investigativo como cobertura: qué evidencia debería haber producido un alcance de recolección, qué falta, qué es incierto y qué quedó fuera de alcance.
- [**sudo-su**](https://github.com/annatchijova/sudo-su) — Investigación jugable de forense Linux en diez niveles: filesystem, permisos, procesos, logs, sockets, timelines, auditd y escalada de privilegios.
- [**annacondaa**](https://github.com/annatchijova/annacondaa) — *Privado.* Línea complementaria de ANNACONDA para análisis de casos y flujos de investigación centrados en evidencia.
- [**hackers-argentina**](https://github.com/annatchijova/hackers-argentina) — *Privado.* Recursos curados de ciberseguridad argentina.
- [**logs**](https://github.com/annatchijova/logs) — *Privado.* Trazas operativas y artefactos relacionados.

### Criptografía y registros verificables

- [**continuum**](https://github.com/annatchijova/continuum) — Archivo personal cifrado, local y recuperable (ver arriba).
- [**proof**](https://github.com/annatchijova/proof) — Verificación de pagos contra el ledger de Stellar (ver arriba).
- [**digital-legacy**](https://github.com/annatchijova/digital-legacy) — *Privado.* Antecesor de CONTINUUM: archivos personales cifrados, legado digital y acceso gobernado a los registros.
- [**audit-chain**](https://github.com/annatchijova/audit-chain) — Registros append-only en C, Java y Rust comparados, con cadenas SHA-256 para detectar modificación, inserción, borrado o reordenamiento.
- [**veridra**](https://github.com/annatchijova/veridra) — Verificador de afirmaciones de pago en Monad: contrasta transacciones con evidencia de la cadena y registra adjudicaciones deterministas.
- [**muster**](https://github.com/annatchijova/muster) — Mercado on-chain con colateral para reservar capacidad de respuesta a incidentes, transferir reservas no utilizadas y hacer cumplir plazos y resolución de disputas.
- [**zk-criptografia**](https://github.com/annatchijova/zk-criptografia) — Investigación en español sobre los fundamentos criptográficos, matemáticos, legales y de identidad experta de la atestación forense de conocimiento cero.

### Memoria, procedencia e historial de agentes

- [**mneme**](https://github.com/annatchijova/mneme) — Trata las memorias de agentes como evidencia forense: separa custodia de autoridad, sigue la contaminación hasta decisiones posteriores, reconstruye impacto y exporta bundles verificables offline.
- [**mneme_memory_mcp**](https://github.com/annatchijova/mneme_memory_mcp) — *Privado.* Integración MCP que conecta la memoria de Mneme con flujos de agentes compatibles.
- [**engram**](https://github.com/annatchijova/engram) — Superficie XR para inspeccionar procedencia, custodia y grants de autoridad de la memoria MNEME, recorridos causales, contrafactuales y exportaciones verificables de forma independiente.
- [**raven-memory**](https://github.com/annatchijova/raven-memory) — Reemplaza la recuperación top-k plana por un campo de memoria adaptativo con refuerzo, olvido, contradicciones, resonancia, inhibición y consolidación. En su benchmark publicado obtiene recall@5 de 0,69 frente a 0,57–0,59 de top-k simple.
- [**raven-memory_**](https://github.com/annatchijova/raven-memory_) — *Privado.* Continuación del desarrollo de Raven Memory.
- [**remember-the-seasons**](https://github.com/annatchijova/remember-the-seasons) — Registra qué memorias se ofrecieron, usaron y reforzaron; sella comprobantes reproducibles y reconstruye estados pasados a partir del historial.
- [**cronos**](https://github.com/annatchijova/cronos) — Registrador black-box para agentes: captura en el momento memorias recuperadas, herramientas llamadas, hipótesis consideradas o descartadas, evidencia y decisiones, y sella la traza en una cadena SHA-256.
- [**stigmergy**](https://github.com/annatchijova/stigmergy) — Memoria multiagente descentralizada: coordinación mediante estado en CockroachDB, hash chains por nodo y un ledger Merkle encadenado, sin orquestador central ni LLM en la ruta de decisión.

### IA adversarial, manipulación y decisiones de alto impacto

- [**mutante**](https://github.com/annatchijova/mutante) — Evaluación adversarial de LLM por mutación de prompts: probes repetidos, scoring determinista, trazas selladas y observabilidad por familia de ataque.
- [**mutante_**](https://github.com/annatchijova/mutante_) — *Privado.* Línea complementaria de investigación de Mutante.
- [**argos**](https://github.com/annatchijova/argos) — Analiza textos desde 11 marcos filosóficos y lingüísticos, con evidencia por marco y señales reproducibles basadas en reglas; la lectura semántica de Gemini queda en una capa separada.
- [**wolf-and-cronos**](https://github.com/annatchijova/wolf-and-cronos) — Análisis de ingeniería social desde seis marcos con gate de corroboración y trazas CRONOS de hipótesis, evidencia, alternativas descartadas y decisiones.
- [**corvus**](https://github.com/annatchijova/corvus) — *Privado.* Aplica seis marcos teóricos y baselines personales a conversaciones de Slack, y exige corroboración antes de escalar.
- [**gambit**](https://github.com/annatchijova/gambit) — Copiloto de negociación que expone señales de presión con lentes deterministas y una lectura semántica separada; el modo WATCH puede clasificar y preparar borradores, pero la decisión de enviar sigue siendo de la persona.
- [**discordia**](https://github.com/annatchijova/discordia) — Experimento reproducible de autonomía acotada: tres módulos de convicción razonan sobre un mismo micromundo, y las contradicciones activan coerción mecánica y un registro persistente de incompatibilidades.
- [**ariadne**](https://github.com/annatchijova/ariadne) — Gobierna decisiones de ML de alto riesgo: las señales GraphSAGE para AML deben corroborarse con reglas deterministas, y las decisiones se sellan y se vinculan al linaje de modelo y datos en DataHub.
- [**fintech**](https://github.com/annatchijova/fintech) — Triage determinista de alertas AML que las ordena por riesgo y pérdida esperada, en vez de heredar la severidad que asignó un scanner.

### Herramientas para desarrollo

- [**crucible**](https://github.com/annatchijova/crucible) — Compila skills de agentes (`SKILL.md`) como contratos trazables, analiza su composición y prueba los controles mediante mutaciones y replay conductual.
- [**cuartel**](https://github.com/annatchijova/cuartel) — Registro MCP para una flota de herramientas forenses, con renderers para Claude Code, Codex y OpenCode.
- [**koine**](https://github.com/annatchijova/koine) — Gate de integridad para documentación multilingüe: sigue bloques fuente y traducciones por hash, y hace fallar CI ante contenido desactualizado, alterado o sin fuente.
- [**to-build-a-fire**](https://github.com/annatchijova/to-build-a-fire) — Captura una instantánea de solo lectura del merge request, comprueba invariantes acotados de autorización y presenta la evidencia pendiente para revisión humana.
- [**stylometry-ci**](https://github.com/annatchijova/stylometry-ci) — Herramientas privadas de integración continua para el proyecto Stylometry.
- [**phylo**](https://github.com/annatchijova/phylo) — Optimización evolutiva de código: un LLM propone mutaciones, candidatos aislados corren pruebas y benchmarks, y un bundle firmado vuelve reproducible el cambio ganador.

### Personas, coordinación y beneficio social

- [**compass**](https://github.com/annatchijova/compass) — Exploración vocacional abductiva: mantiene hipótesis rivales, propone experimentos en el mundo real y solo actualiza sus índices sellados con evidencia validada por la persona. No es un veredicto de personalidad.
- [**impetu**](https://github.com/annatchijova/impetu) — Agente proactivo para personas autistas y con TDAH: acuerda un próximo paso según la energía disponible, usa Gmail y Calendar, mantiene memoria y vuelve con seguimientos programados.
- [**lifeline**](https://github.com/annatchijova/lifeline) — Coordinación humanitaria: valida restricciones y procedencia de pedidos, recursos, rutas y refugios, genera propuestas de despacho inspeccionables y registra aprobaciones humanas.
- [**aporia**](https://github.com/annatchijova/aporia) — Convierte preferencias, disponibilidad, presupuestos y restricciones de un grupo en un plan compartido viable; si no hay ninguno, identifica los cambios mínimos que lo harían posible.
- [**hivemind_tidal**](https://github.com/annatchijova/hivemind_tidal) — Monitoreo de lecturas hidrológicas que detecta contradicciones entre sensores, con trazabilidad y alertas, aplicado a la prevención de inundaciones.
- [**mise**](https://github.com/annatchijova/mise) — App MCP determinista para despensa, vencimientos, planificación de comidas, sesiones de cocina reanudables, sustituciones y listas de compras.
- [**nexo**](https://github.com/annatchijova/nexo) — Casos de derechos digitales en Argentina: separa evidencia fuente, afirmaciones, hechos derivados, inferencias acotadas, reclamos legales y acciones posibles; prepara solicitudes, pero no las presenta.
- [**locoporcolt**](https://github.com/annatchijova/locoporcolt) — *Privado.* Marketplace regulado que conecta vendedores y compradores sin custodiar el pago ni intermediar la transferencia regulada.
- [**proyectohermana**](https://github.com/annatchijova/proyectohermana) — *Privado.* Derechos humanos y apoyo comunitario.

### Medios interactivos y accesibilidad

- [**f1-mythos**](https://github.com/annatchijova/f1-mythos) — Museo bilingüe y autocontenido de curiosidades de Fórmula 1, con tarjetas fact-or-myth, navegación táctil y estado de juego local.
- [**pichon**](https://github.com/annatchijova/pichon) — Interfaz satírica que se presenta como plataforma nacional de identificación ornitológico-humana y contrainteligencia.
- [**poes-cabinet**](https://github.com/annatchijova/poes-cabinet) — *Privado.* Escape room offline point-and-click: cuatro paredes navegables, inventario, puzzles de lógica y criptografía, pistas y progreso guardado.
- [**sonya**](https://github.com/annatchijova/sonya) — Notaría de medios generativos: audita el prompt, genera e inspecciona un asset, aplica correcciones y sella prompt, salida, corrección y veredicto.
- [**rebound**](https://github.com/annatchijova/rebound) — Concepto de navegación interior con sonar biomimético para la orientación de personas con discapacidad visual.
- [**splapground**](https://github.com/annatchijova/splapground) — Concepto de juego de realidad mixta sentado para Meta Quest.

### Skills para agentes

- [**SKILLS**](https://github.com/annatchijova/SKILLS) — 92 skills para agentes de programación, cada una con disparadores y un método práctico. Convierten investigación abductiva, epistemología, seguridad, forense e ingeniería en procedimientos reutilizables.
