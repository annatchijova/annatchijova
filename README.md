# Anna Tchijova

**English** · [Español](README.es.md) · [LinkedIn](https://www.linkedin.com/in/anna-tchijova/)

Hi, I'm Anna Tchijova. I was born in Russia and I live in Argentina. I'm a Formula 1 fan —McLaren and Alain Prost, specifically—, a sentientist, and I practice effective altruism. And now I build systems! Almost all of them under Apache 2.0 or MIT.

Research has always been one of my passions; the other is signature cuisine, where I built my professional career. The kitchen taught me to work *safety first*: reduce errors, keep traceability, lower risk, run many processes at once and make the most of every minute. Ten tickets come in and you need a coordinated team doing things right, because everything depends on everything else, and one small mistake can end in a ruined plate or in food poisoning.

I've read a lot my whole life —a lot— and I always had good ideas, but I wasn't a programmer. LLMs changed that: they help you with syntax, but they don't replace human judgment. They're like good colleagues who can also be wrong. I built my first project with seven different LLMs from the web, making them debate each other in turns —endless debates— to understand their alignments and biases. Then I discovered CLIs and moved to a hybrid way of working: multiple terminals and agents, plus some that stayed on the web.

I don't want a team that tells me everything is fine, and you can see that in my 92 skills, built with the methodology I learned over years of Social Sciences, research, logic, philosophy, semiotics and epistemology. I don't need fast, disposable or insecure results. I'd rather follow a method that lets me build coherently, layer by layer, without leaving loose bugs "for later".

Besides researching human rights and non-human rights, I'm an independent security and AI researcher: vulnerability research, DFIR, agentic systems, OSINT/HUMINT and verifiable security architectures.

I've done many epistemological jailbreaks on LLMs with a single goal: making what I build safe. I never published them —not the prompts, and even less the responses—; that's part of my ethics. I don't have a "hacker ego" to protect. Finding bugs in my own systems is an opportunity: math doesn't care about ego.

**I'd love for people to red-team my systems, and I give my explicit consent to do so.**

I have over 15 years of experience in multidisciplinary research, profiling and behavior: paying attention to what is said, how, when, where, why and what for. I've studied human behavior since I was 8, LLM behavior since 2023, and I've been reporting security vulnerabilities since 2025. Since childhood I've been drawn to forensics, cryptography, physics, intelligence and counterintelligence, OSINT, HUMINT and SIGINT.

---

## Method

My method is grounded in the scientific method and Peircean abduction: I formulate rival explanations for an observation, deduce what should happen if each one were true, and test those predictions with the intention of refuting them. In security research, failed hypotheses are evidence too.

I keep negative results, document known limitations and design tests around falsifiable invariants, not demos that only confirm what was expected. Reproducibility and adversarial review are part of the research output, not a cleanup task for later.

That's why —haha— every repo of mine has a `/docs` folder that can hold dozens or hundreds of documents: red-team rounds, why I build what I build, what I did and what failed, why I made one decision and not another.

---

## Research lines

**Vulnerability research.** I study failures at trust and authority boundaries: representation mismatches, confused deputy, SSRF, validation/action divergence and composition failures. My work includes runnable PoCs, variant analysis, coordinated disclosure and security fixes merged upstream. Every audit ends in a professional report that separates what was audited from what wasn't, and confirmed findings from falsified and possible ones.

**DFIR and deterministic systems.** I build forensic systems where evidence, inference and narration stay separate, decisions are reproducible, and probabilistic models never silently gain authority over conclusions. In many cases I rely on the Daubert standard.

**AI, agents and engineering.** I research model behavior, tool use, agent authority, memory and provenance, adversarial evaluation, manipulation and bounded autonomy, especially when automated decisions affect people. On the engineering side I work on multi-agent orchestration, harness design, evaluation, testing and engineering discipline. I'm at home orchestrating and coordinating agents, and building harnesses.

**OSINT/HUMINT.** My background in Social Sciences and human rights research shapes an OSINT/HUMINT practice focused on assessing sources, testing hypotheses against each other, corroborating, following contradictions and provenance, and making uncertainty explicit. My interest in forensics, intelligence and counterintelligence started in childhood and is part of the same research path.

---

## Featured projects

### [VIGÍA](https://github.com/annatchijova/vigia-intent-analysis)

Formalizes forensic intent analysis as an executable deterministic system. It combines abductive reasoning, cross-artifact analysis, explicit uncertainty and abstention, exact arithmetic for decisions, sealed evidence packages and adversarial self-audit. It extends Indicators of Compromise (IoC) with Indicators of Intent (IoI) to analyze logical, contextual and behavioral fractures that can tell apart error, anomaly, deliberate action, concealment and manipulation. LLMs can investigate or narrate; they don't control the verdict.

### [JANUS](https://github.com/annatchijova/janus) · private repo, preparing launch for SMBs

An adversarial social engineering simulator that measures how people make decisions under contextual uncertainty, not whether they clicked. It treats overreaction and credulity as symmetric failures, records decision processes across benign, malicious and ambiguous cases, and produces individual and organizational reports.

### [ANNACONDA](https://github.com/annatchijova/annaconda)

Extends forensic investigation to endpoint and fleet acquisition: bounded evidence collection through Velociraptor and telemetry, normalized evidence windows, manifests and chain of custody. The live system runs a fleet of Google ADK agents: agents investigate and delegate, while deterministic code seals and adjudicates the window before any model narrates it.

### [VELO](https://github.com/annatchijova/velo)

Zero-knowledge (ZK) forensic attestation on Midnight: the verdict is public, the evidence stays private. A deterministic engine analyzes local evidence with exact rational arithmetic, corroboration gates and chain of custody, plus a mandatory Devil's Advocate step before a MALICE verdict is allowed. A Compact circuit proves defined constraints without revealing the case. The full flow runs from local analysis to sealed bundle, ZK proof, on-chain attestation and independent verification.

### [STYLOMETRY-CI](https://github.com/annatchijova/stylometry)

A forensic identity gate for GitLab pipelines. Seven independent forensic cores compare a commit against the behavioral and stylistic baseline of the person or LLM listed as author —behavioral patterns, entropy, semiotics, lexical and register shifts, chronobiology, commit atomicity and syntactic fingerprints— and produce deterministic PASS / WARN / REQUIRE_REVIEW / BLOCK results with exact rational arithmetic.

### [PHYLO-Google](https://github.com/annatchijova/phylo-google) · private code, available on request

The PHYLO line for Google's platform. In this evolutionary code optimization system, the model proposes mutations, isolated sandboxes (Pyodide/WASM and V8) run the candidates, and tests and benchmarks select the changes. A signed Evolution Bundle, verifiable offline, records the baseline, the mutations, the winning candidate and the measurements.

### Applied cryptography: CONTINUUM · PROOF · VELO

A research line on how cryptographic mechanisms can make decisions, evidence and sensitive state independently verifiable, without exposing more information than necessary.

- **CONTINUUM** is an encrypted, local, recoverable life archive: AES-256-GCM, SHA-256 audit chains, deterministic classification and retrieval, access policies and Shamir Secret Sharing for threshold recovery. Optional AI narration only receives already-selected evidence and cannot alter ranking, access, integrity or release decisions.
- **PROOF** verifies payment claims against the Stellar ledger instead of trusting screenshots or data declared by the payer. It reconstructs the transaction facts, checks each claim separately, distinguishes VERIFIED / NOT VERIFIED / INSUFFICIENT EVIDENCE and seals the package with canonical serialization and SHA-256. Its independent verifier detects later tampering; it was exercised end-to-end on Stellar Testnet.
- **VELO** (above) takes the same idea to forensic attestation: only a commitment, the declared verdict and the proof reach the chain, and the circuit constraints prevent producing an invalid attestation by bypassing application-level checks.

Together they explore verifiability without unnecessary disclosure: encrypted local custody, fact verification on a public ledger, and privacy-preserving forensic attestation.

---

## Catalog

Repositories grouped by area. Those marked *private* are available on request or under closed development.

### Forensics, DFIR and investigation tools

- [**zaynor**](https://github.com/annatchijova/zaynor) — Local AI-assisted DFIR platform: normalizes and freezes evidence before VIGÍA's deterministic analysis; then lets you explain sealed findings or extend the investigation with read-only queries via CLI, web, API and MCP.
- [**vigia**](https://github.com/annatchijova/vigia) — Hub for the VIGÍA project and supporting materials.
- [**vigia-cases**](https://github.com/annatchijova/vigia-cases) — Reproducible DFIR benchmark: case material and ground truth kept separate, MITRE ATT&CK mapping, SHA-256 manifests and scoring guide.
- [**forge**](https://github.com/annatchijova/forge) — Local, read-only runtime for reproducible repository audits: specialized analyzers with explicit contracts, preserved evidence and discarded hypotheses, and sealed findings for CLI, Python and MCP.
- [**forge-improved**](https://github.com/annatchijova/forge-improved) — Multi-language line of Forge, with multi-agent auditing and explicit abstention when the scope can't support a conclusion.
- [**forge-results**](https://github.com/annatchijova/forge-results) — Per-run manifests, benchmarks and reports, kept separate from the runtime to preserve attribution and reproducibility.
- [**orbit-guardian**](https://github.com/annatchijova/orbit-guardian) — Intent analysis for merge requests: independent forensic cores examine obfuscated payloads, manipulation and social engineering, and require corroboration before presenting the sealed result to reviewers.
- [**pancito-red-team**](https://github.com/annatchijova/pancito-red-team) — Each bounded adversarial validation links an observable change in the target to a control failure and to the defensive telemetry that recorded it.
- [**moira**](https://github.com/annatchijova/moira) — Uses exact rational arithmetic to find the minimal causal cut of a deterministic history: which transitions can be removed to change the outcome.
- [**siberian**](https://github.com/annatchijova/siberian) — Models investigative silence as coverage: what evidence a collection scope should have produced, what's missing, what's uncertain and what fell out of scope.
- [**sudo-su**](https://github.com/annatchijova/sudo-su) — Playable Linux forensics investigation in ten levels: filesystem, permissions, processes, logs, sockets, timelines, auditd and privilege escalation.
- [**annacondaa**](https://github.com/annatchijova/annacondaa) — *Private.* Companion line to ANNACONDA for case analysis and evidence-centered investigation workflows.
- [**hackers-argentina**](https://github.com/annatchijova/hackers-argentina) — *Private.* Curated Argentine cybersecurity resources.
- [**logs**](https://github.com/annatchijova/logs) — *Private.* Operational traces and related artifacts.

### Cryptography and verifiable records

- [**continuum**](https://github.com/annatchijova/continuum) — Encrypted, local, recoverable personal archive (see above).
- [**proof**](https://github.com/annatchijova/proof) — Payment verification against the Stellar ledger (see above).
- [**digital-legacy**](https://github.com/annatchijova/digital-legacy) — *Private.* Predecessor of CONTINUUM: encrypted personal archives, digital legacy and governed access to records.
- [**audit-chain**](https://github.com/annatchijova/audit-chain) — Append-only logs compared across C, Java and Rust, with SHA-256 chains to detect modification, insertion, deletion or reordering.
- [**veridra**](https://github.com/annatchijova/veridra) — Payment claim verifier on Monad: checks transactions against on-chain evidence and records deterministic adjudications.
- [**muster**](https://github.com/annatchijova/muster) — Collateralized on-chain market to reserve incident response capacity, transfer unused reservations, and enforce service deadlines and dispute resolution.
- [**zk-criptografia**](https://github.com/annatchijova/zk-criptografia) — Spanish-language research on the cryptographic, mathematical, legal and expert-identity foundations of zero-knowledge forensic attestation.

### Agent memory, provenance and history

- [**mneme**](https://github.com/annatchijova/mneme) — Treats agent memories as forensic evidence: separates custody from authority, traces contamination into later decisions, reconstructs impact and exports offline-verifiable bundles.
- [**mneme_memory_mcp**](https://github.com/annatchijova/mneme_memory_mcp) — *Private.* MCP integration connecting Mneme memory to compatible agent workflows.
- [**engram**](https://github.com/annatchijova/engram) — XR surface to inspect provenance, custody and authority grants of MNEME memory, causal paths, counterfactuals and independently verifiable exports.
- [**raven-memory**](https://github.com/annatchijova/raven-memory) — Replaces flat top-k retrieval with an adaptive memory field featuring reinforcement, forgetting, contradictions, resonance, inhibition and consolidation. On its published benchmark it reaches recall@5 of 0.69 versus 0.57–0.59 for plain top-k.
- [**raven-memory_**](https://github.com/annatchijova/raven-memory_) — *Private.* Ongoing development of Raven Memory.
- [**remember-the-seasons**](https://github.com/annatchijova/remember-the-seasons) — Records which memories were offered, used and reinforced; seals reproducible receipts and reconstructs past states from history.
- [**cronos**](https://github.com/annatchijova/cronos) — Black-box recorder for agents: captures retrieved memories, tool calls, considered or discarded hypotheses, evidence and decisions as they happen, and seals the trace in a SHA-256 chain.
- [**stigmergy**](https://github.com/annatchijova/stigmergy) — Decentralized multi-agent memory: coordination through CockroachDB state, per-node hash chains and a chained Merkle ledger, with no central orchestrator or LLM in the decision path.

### Adversarial AI, manipulation and high-stakes decisions

- [**mutante**](https://github.com/annatchijova/mutante) — Adversarial LLM evaluation by prompt mutation: repeated probes, deterministic scoring, sealed traces and per-attack-family observability.
- [**mutante_**](https://github.com/annatchijova/mutante_) — *Private.* Companion research line for Mutante.
- [**argos**](https://github.com/annatchijova/argos) — Analyzes texts through 11 philosophical and linguistic frameworks, with per-framework evidence and reproducible rule-based signals; Gemini's semantic reading stays in a separate layer.
- [**wolf-and-cronos**](https://github.com/annatchijova/wolf-and-cronos) — Social engineering analysis through six frameworks with a corroboration gate and CRONOS traces of hypotheses, evidence, discarded alternatives and decisions.
- [**corvus**](https://github.com/annatchijova/corvus) — *Private.* Applies six theoretical frameworks and personal baselines to Slack conversations, and requires corroboration before escalating.
- [**gambit**](https://github.com/annatchijova/gambit) — Negotiation copilot that surfaces pressure signals through deterministic lenses and a separate semantic reading; WATCH mode can classify and draft, but the decision to send stays with the person.
- [**discordia**](https://github.com/annatchijova/discordia) — Reproducible bounded-autonomy experiment: three conviction modules reason about the same microworld, and contradictions trigger mechanical coercion and a persistent incompatibility log.
- [**ariadne**](https://github.com/annatchijova/ariadne) — Governs high-risk ML decisions: GraphSAGE AML signals must be corroborated by deterministic rules, and decisions are sealed and linked to model and data lineage in DataHub.
- [**fintech**](https://github.com/annatchijova/fintech) — Deterministic AML alert triage that ranks alerts by risk and expected loss instead of inheriting scanner-assigned severity.

### Developer tools

- [**crucible**](https://github.com/annatchijova/crucible) — Compiles agent skills (`SKILL.md`) into traceable contracts, analyzes their composition and tests the controls through mutation and behavioral replay.
- [**cuartel**](https://github.com/annatchijova/cuartel) — MCP registry for a fleet of forensic tools, with renderers for Claude Code, Codex and OpenCode.
- [**koine**](https://github.com/annatchijova/koine) — Integrity gate for multilingual documentation: tracks source blocks and translations by hash, and fails CI on stale, altered or sourceless content.
- [**to-build-a-fire**](https://github.com/annatchijova/to-build-a-fire) — Takes a read-only snapshot of a merge request, checks bounded authorization invariants and surfaces pending evidence for human review.
- [**stylometry-ci**](https://github.com/annatchijova/stylometry-ci) — Private continuous-integration tooling for the Stylometry project.
- [**phylo**](https://github.com/annatchijova/phylo) — Evolutionary code optimization: an LLM proposes mutations, isolated candidates run tests and benchmarks, and a signed bundle makes the winning change reproducible.

### People, coordination and social good

- [**compass**](https://github.com/annatchijova/compass) — Abductive career exploration: keeps rival hypotheses, proposes real-world experiments and only updates its sealed indices with evidence validated by the person. It's not a personality verdict.
- [**impetu**](https://github.com/annatchijova/impetu) — Proactive agent for autistic and ADHD people: agrees on a next step based on available energy, uses Gmail and Calendar, keeps memory and comes back with scheduled follow-ups.
- [**lifeline**](https://github.com/annatchijova/lifeline) — Humanitarian coordination: validates constraints and provenance of requests, resources, routes and shelters, generates inspectable dispatch proposals and records human approvals.
- [**aporia**](https://github.com/annatchijova/aporia) — Turns a group's preferences, availability, budgets and constraints into a viable shared plan; if none exists, identifies the minimal changes that would make one possible.
- [**hivemind_tidal**](https://github.com/annatchijova/hivemind_tidal) — Hydrological reading monitor that detects contradictions between sensors, with traceability and alerts, applied to flood prevention.
- [**mise**](https://github.com/annatchijova/mise) — Deterministic MCP app for pantry inventory, expiration dates, meal planning, resumable cooking sessions, substitutions and shopping lists.
- [**nexo**](https://github.com/annatchijova/nexo) — Digital rights cases in Argentina: separates source evidence, claims, derived facts, bounded inferences, legal claims and possible actions; prepares requests but doesn't file them.
- [**locoporcolt**](https://github.com/annatchijova/locoporcolt) — *Private.* Regulated marketplace connecting sellers and buyers without holding the payment or intermediating the regulated transfer.
- [**proyectohermana**](https://github.com/annatchijova/proyectohermana) — *Private.* Human rights and community support.

### Interactive media and accessibility

- [**f1-mythos**](https://github.com/annatchijova/f1-mythos) — Self-contained bilingual museum of Formula 1 trivia, with fact-or-myth cards, touch navigation and local game state.
- [**pichon**](https://github.com/annatchijova/pichon) — Satirical interface posing as a national ornithological-human identification and counterintelligence platform.
- [**poes-cabinet**](https://github.com/annatchijova/poes-cabinet) — *Private.* Offline point-and-click escape room: four navigable walls, inventory, logic and cryptography puzzles, hints and saved progress.
- [**sonya**](https://github.com/annatchijova/sonya) — Generative media notary: audits the prompt, generates and inspects an asset, applies corrections and seals prompt, output, correction and verdict.
- [**rebound**](https://github.com/annatchijova/rebound) — Indoor navigation concept using biomimetic sonar to help visually impaired people find their way.
- [**splapground**](https://github.com/annatchijova/splapground) — Seated mixed-reality game concept for Meta Quest.

### Agent skills

- [**SKILLS**](https://github.com/annatchijova/SKILLS) — 92 skills for coding agents, each with triggers and a practical method. They turn abductive research, epistemology, security, forensics and engineering into reusable procedures.
