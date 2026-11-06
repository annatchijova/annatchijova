# Анна Чижова

[English](README.md) · [Español](README.es.md) · **Русский** · [LinkedIn](https://www.linkedin.com/in/anna-tchijova/)

Я Анна Чижова. Я родилась в России и живу в Аргентине. Я независимый исследователь в области безопасности и искусственного интеллекта: vulnerability research, DFIR, агентные системы, OSINT/HUMINT и проверяемые архитектуры безопасности.

Я также исследую права человека и нечеловеческие права. Мой профессиональный опыт в авторской кухне научил меня работать по принципу «сначала безопасность»: снижать количество ошибок, сохранять прослеживаемость, управлять риском и координировать много процессов одновременно.

Я не хочу, чтобы команда просто говорила, что всё хорошо. Поэтому мои 92 skills основаны на социальных науках, исследовании, логике, философии, семиотике и эпистемологии. LLM помогают с синтаксисом, но не заменяют человеческое суждение.

**Я открыто приглашаю людей проводить red-team моих систем и даю на это явное согласие.**

---

## Метод

Мой метод опирается на научный метод и пейрсовскую абдукцию: я формулирую конкурирующие объяснения наблюдения, вывожу проверяемые следствия каждого из них и тестирую их с намерением опровергнуть. Неудачные гипотезы тоже являются данными.

Я сохраняю отрицательные результаты, документирую известные ограничения и строю тесты на фальсифицируемых инвариантах. В моих системах доказательства, решения и повествование разделены: LLM может исследовать или объяснять, но детерминированное ядро принимает и запечатывает решение.

---

## Избранные проекты

### [VIGÍA](https://github.com/annatchijova/vigia-intent-analysis)

Детерминированная система судебно-криминалистического анализа намерений. Она объединяет абдуктивное рассуждение, анализ нескольких артефактов, явную неопределённость и воздержание, точную арифметику, запечатанные пакеты доказательств и adversarial self-audit. LLM могут исследовать или рассказывать, но не управляют вердиктом.

### [KRAKADYL](https://github.com/annatchijova/krakadyl)

Агент активного расследования, сохраняющий доказательства, полномочия и непрерывность дела под давлением времени. ИИ предлагает, а детерминированный движок принимает и запечатывает каждый вердикт до вызова модели: SHA-256 receipts, независимый verifier и правило «reported is not verified». [Живая демонстрация](https://krakadyl-live.vercel.app).

### [ANNACONDA](https://github.com/annatchijova/annaconda)

Расширяет расследование до endpoint и fleet acquisition: ограниченный сбор доказательств через Velociraptor и телеметрию, нормализованные окна доказательств, manifests и chain of custody.

### [VELO](https://github.com/annatchijova/velo)

Zero-knowledge attestation судебно-криминалистических вердиктов на Midnight: вердикт публичен, доказательства остаются приватными. Детерминированный движок анализирует локальные доказательства, а Compact circuit доказывает заданные ограничения без раскрытия дела.

### [STYLOMETRY-CI](https://github.com/annatchijova/stylometry)

Судебно-криминалистический identity gate для GitLab pipelines. Независимые ядра сравнивают commit с поведенческой и стилистической базой автора и выдают детерминированные PASS / WARN / REQUIRE_REVIEW / BLOCK.

### Прикладная криптография: CONTINUUM · PROOF · VELO

Исследовательская линия о том, как сделать решения, доказательства и чувствительные состояния независимо проверяемыми без лишнего раскрытия данных.

---

## Каталог

Репозитории сгруппированы по направлениям. Пометка *private* означает закрытую разработку или доступ по запросу.

### Forensics, DFIR и расследования

- [**vigia**](https://github.com/annatchijova/vigia) — центр проекта VIGÍA и связанные материалы.
- [**vigia-intent-analysis**](https://github.com/annatchijova/vigia-intent-analysis) — движок анализа намерений DFIR.
- [**vigia-intent-analysis-docs**](https://github.com/annatchijova/vigia-intent-analysis-docs) — испаноязычный архив академической документации VIGÍA.
- [**krakadyl**](https://github.com/annatchijova/krakadyl) — агент активного расследования с детерминированным sealed verdict.
- [**zaynor**](https://github.com/annatchijova/zaynor) — локальная DFIR-платформа с AI-assisted analysis.
- [**vigia-cases**](https://github.com/annatchijova/vigia-cases) — воспроизводимый DFIR benchmark с ground truth и ATT&CK mapping.
- [**dynamic-incident-response-es**](https://github.com/annatchijova/dynamic-incident-response-es) — техническое учебное руководство на испанском по *Dynamic Incident Response: A Framework for Security Teams* Джошуа Райта, при участии Райана Чапмана, Меган Родди-Фонсека и Дина Парсонса. Это не перевод книги, а самостоятельный технический синтез по главам; каждый файл указывает точный источник, который он обобщает.
- [**annaconda**](https://github.com/annatchijova/annaconda) — автономный DFIR agent fleet.
- [**pancito-red-team**](https://github.com/annatchijova/pancito-red-team) — ограниченная adversary validation с воспроизводимыми доказательствами.
- [**orbit-guardian**](https://github.com/annatchijova/orbit-guardian) — forensic MR audit skill для GitLab Orbit.
- [**moira**](https://github.com/annatchijova/moira) — минимальный причинный cut детерминированной истории.
- [**siberian**](https://github.com/annatchijova/siberian) — анализ следственной тишины и отсутствующих доказательств.
- [**sudo-su**](https://github.com/annatchijova/sudo-su) — интерактивное расследование Linux forensics.
- [**forge-improved**](https://github.com/annatchijova/forge-improved) — multi-language forensic repository governance engine.
- [**forge-results**](https://github.com/annatchijova/forge-results) — manifests, benchmarks и отчёты Forge.
- [**annacondaa**](https://github.com/annatchijova/annacondaa) — *private*, companion line ANNACONDA.

### Криптография и проверяемые записи

- [**continuum**](https://github.com/annatchijova/continuum) — локальный зашифрованный и восстанавливаемый архив.
- [**proof**](https://github.com/annatchijova/proof) — проверка платёжных утверждений по Stellar ledger.
- [**velo**](https://github.com/annatchijova/velo) — zero-knowledge forensic attestation.
- [**zk-criptografia**](https://github.com/annatchijova/zk-criptografia) — публичная испаноязычная база знаний о zero-knowledge cryptography и судебно-криминалистической аттестации.
- [**audit-chain**](https://github.com/annatchijova/audit-chain) — append-only logs и SHA-256 chains в C, Java и Rust.
- [**the-black-ledger**](https://github.com/annatchijova/the-black-ledger) — проверяемый ledger общих расходов.
- [**veridra**](https://github.com/annatchijova/veridra) — on-chain payment verification на Monad.
- [**muster**](https://github.com/annatchijova/muster) — on-chain рынок будущей capacity специалистов.

### Память, происхождение и история агентов

- [**mneme**](https://github.com/annatchijova/mneme) — память агентов как доказательство с chain of custody.
- [**engram**](https://github.com/annatchijova/engram) — XR-интерфейс для проверяемой памяти MNEME.
- [**raven-memory**](https://github.com/annatchijova/raven-memory) — adaptive memory substrate для agentic AI.
- [**remember-the-seasons**](https://github.com/annatchijova/remember-the-seasons) — receipts и реконструкция прошлых состояний памяти.
- [**cronos**](https://github.com/annatchijova/cronos) — black-box recorder для AI agents.
- [**stigmergy**](https://github.com/annatchijova/stigmergy) — децентрализованная multi-agent memory.
- [**mneme_memory_mcp**](https://github.com/annatchijova/mneme_memory_mcp) — *private*, MCP integration Mneme.

### Adversarial AI и решения высокого риска

- [**mutante**](https://github.com/annatchijova/mutante) — adversarial LLM evaluation.
- [**argos**](https://github.com/annatchijova/argos) — 11 philosophical and linguistic frameworks для анализа текстов.
- [**wolf-and-cronos**](https://github.com/annatchijova/wolf-and-cronos) — детерминированный анализ social engineering.
- [**gambit**](https://github.com/annatchijova/gambit) — negotiation copilot с human-controlled send.
- [**discordia**](https://github.com/annatchijova/discordia) — эксперимент bounded autonomy.
- [**reward-hacking-social**](https://github.com/annatchijova/reward-hacking-social) — исследовательский корпус о reward hacking как социотехническом явлении.
- [**ariadne**](https://github.com/annatchijova/ariadne) — auditable AML verdicts в DataHub.
- [**fintech**](https://github.com/annatchijova/fintech) — детерминированный AML alert triage.
- [**corvus**](https://github.com/annatchijova/corvus) — *private*, анализ разговоров Slack.

### Инструменты разработки и исследовательская документация

- [**crucible**](https://github.com/annatchijova/crucible) — компиляция agent skills в traceable contracts.
- [**cuartel**](https://github.com/annatchijova/cuartel) — MCP registry forensic tool fleet.
- [**koine**](https://github.com/annatchijova/koine) — integrity gate для многоязычной документации.
- [**to-build-a-fire**](https://github.com/annatchijova/to-build-a-fire) — evidence-driven review для agentic DevSecOps.
- [**funes-the-memorious**](https://github.com/annatchijova/funes-the-memorious) — verifiable build provenance и test evidence для QNX 8.0.
- [**necromancer**](https://github.com/annatchijova/necromancer) — software archaeology для заброшенных проектов.
- [**investigaciones**](https://github.com/annatchijova/investigaciones) — архив исследовательских отчётов, созданных с помощью ИИ.
- [**vigia-intent-analysis-docs**](https://github.com/annatchijova/vigia-intent-analysis-docs) — исследовательская и академическая документация линии forensic intent analysis VIGÍA.
- [**zk-criptografia**](https://github.com/annatchijova/zk-criptografia) — испаноязычное исследование zero-knowledge cryptography, forensic attestation и экспертной идентичности.
- [**reward-hacking-social**](https://github.com/annatchijova/reward-hacking-social) — исследование reward hacking как социотехнического явления с точки зрения социальных наук.
- [**dynamic-incident-response-es**](https://github.com/annatchijova/dynamic-incident-response-es) — техническое учебное руководство на испанском по *Dynamic Incident Response: A Framework for Security Teams* Джошуа Райта, при участии Райана Чапмана, Меган Родди-Фонсека и Дина Парсонса. Это не перевод книги, а самостоятельный технический синтез по главам; каждый файл указывает точный источник, который он обобщает.
- [**skills-comunicacion**](https://github.com/annatchijova/skills-comunicacion) — *private*, skills по коммуникации и исследованию, отдельно от публичной коллекции инженерных skills.
- [**SKILLS**](https://github.com/annatchijova/SKILLS) — 92 оригинальные skills для агентной разработки.
- [**hackers-argentina**](https://github.com/annatchijova/hackers-argentina) — *private*, аргентинские ресурсы по кибербезопасности; доступ по разрешению.

### Люди, координация и социальное благо

- [**compass**](https://github.com/annatchijova/compass) — abductive career discovery.
- [**impetu**](https://github.com/annatchijova/impetu) — proactive assistant для аутичных людей и людей с ADHD.
- [**lifeline**](https://github.com/annatchijova/lifeline) — inspectable humanitaria coordination.
- [**aporia**](https://github.com/annatchijova/aporia) — совместное планирование с ограничениями группы.
- [**mise**](https://github.com/annatchijova/mise) — детерминированный MCP-помощник для кухни и покупок.
- [**nexo**](https://github.com/annatchijova/nexo) — verifiable digital-rights case graph.

### Интерактивные медиа и доступность

- [**f1-mythos**](https://github.com/annatchijova/f1-mythos) — двуязычный интерактивный музей Formula 1.
- [**pichon**](https://github.com/annatchijova/pichon) — сатирический интерфейс идентификации и контрразведки.
- [**rebound**](https://github.com/annatchijova/rebound) — biomimetic echolocation для навигации незрячих.
- [**splapground**](https://github.com/annatchijova/splapground) — seated mixed-reality playground для Meta Quest.
- [**sonya**](https://github.com/annatchijova/sonya) — notarization pipeline для generative media.
