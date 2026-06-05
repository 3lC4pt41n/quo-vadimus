# Quo Vadimus — "Where are we going."

[Deutsch](./README.md) · **English**

A scenario of the future, built as a **system of effects**: not a vibe, not a prophecy, but a directed causal graph you can disagree with at a specific point. Every causal link carries a named mechanism ("because…"), a confidence (evidenced / plausible / contested), and a **sign** (+ same-direction / − opposite-direction).

The interactive map lives in [`quo-vadimus.html`](./quo-vadimus.html) — open it in a browser, click a node or an edge to see the mechanism. State: 39 nodes, 75 signed edges, structurally checked (no dead ends, no dangling references). The map's labels are in German; this document is the English reading guide.

## The system in five sentences

Seven independent starting conditions — AI automation, the tax system, the return of power politics, public debt, ecological degeneration, technological/medical progress, and demographics — almost all converge on the same few nodes: **precarization of the salaried middle (and, downstream, of workers)**, a **locational-competition lock** that blocks every national solution, and a contracting **moral circle**. Beneath the chains lies a substrate: the human as an organism that tends to itself first, then family, community, country, and lastly the world — Kantian universalism only in the exceptional state of abundance. Via perceived security (`SEC`), three forces pull the circle inward: precarization itself and two unpriced **externalities** — ecological degeneration and social erosion (felt poverty, homelessness, hopelessness, vandalism, crime). Yet the same future is also rich: automation, AI education, and medical progress generate a massive surplus. **Whether that becomes utopia or dystopia hangs on a single switch — not abundance versus scarcity, but distributed versus captured abundance.**

## The tipping variable

> **Degree of distribution: Is the growing surplus broadly distributed — or captured by a few?**

It sits upstream of everything else (`DIST → SEC` on the map) and is **wired into the graph**, not merely asserted. What pushes it toward capture: the locational-competition lock (`LK`), power-based order (`ORD`), tax mispricing (`S2`), the debt-driven growth imperative (`WZ`), the concentrated upskilling of a few (`Au`), and autocracy (`SYS`). What lifts it: broadly accessible AI education (`EDU`) and the surplus itself (`SURP`). Both poles hang on this one node:

**Utopia route** — broadly distributed → broadly felt prosperity → perceived security rises → the moral circle widens → the locks open (supranational coordination becomes possible) → stabilization.

**Dystopia route** — captured → upskilling for the few, the rest precarious → **abundance without security** → the circle contracts *despite* wealth → social erosion, radicalization, renationalization, power-based order.

The punchline: the dark attractor is not "decline." There is no lack of progress — progress is guaranteed and abundant. The dark attractor is **throttled abundance**: an enormous surplus, narrowly distributed, and therefore not experienced as security. The locks on the map are the machinery of that throttling.

## The bright forks

The system keeps four narrow exits open — visible, so it stays a scenario and not a fate:

**Productive debt** (investing rather than subsidizing consumption) can generate actual growth → positive-sum → wider circle. **AI education at scale** raises the degree of distribution directly and tips the upskilling path: more people into good roles instead of service and redundancy. **External threat** can widen the circle instead of contracting it — "Europe as a bloc," planetary cooperation against a shared climate risk (asymmetrically braked: war integrates, climate fragments). And **demographics** act as an anti-doom counterforce: a shrinking workforce leaves a gap that automation *fills* rather than merely displacing — dampening net job loss (while also driving debt).

## The deeper structure

Three layers: the **surface** (seven chains), the **lock** (`LK` / locational competition, which bolts shut national go-it-alone moves), and the **substrate** (`P` — the concentric moral circle, governed by `SEC`, perceived security). Two **externality engines** mirror each other: ecological degeneration (`ECO`) and social erosion (`SOZ`) — both arise from the system, but their costs fall on society as a whole, and both feed back through `SEC`. Three self-sustaining **feedback loops** hold the dark attractor: renationalization → weaker competitiveness → more pressure → more precarization (`E→C`); precarization → less security → narrower circle → more closure (`C→SEC`); and social erosion → less security for everyone → narrower circle (`SOZ→SEC`).

## Which link don't you believe?

The disagreement at the node is the engine. Three edges I'd attack first (two are already marked *contested* on the map):

1. **"AI makes jobs net-obsolete" (`A → B`, plausible).** Historically, automation rebuilt jobs rather than destroying them (the loom; ATMs → *more* bank tellers). If this edge flips, the first chain breaks at the root.

2. **"High tax wedge → fewer jobs" (`L → J`, contested).** Germany's low unemployment despite a high tax-and-contribution burden is the living counterexample. The employment elasticity is disputed.

3. **The substrate itself (the narrow moral circle, `P`).** If the circle demonstrably *widens* in good times (EU enlargement, global cooperation 1990–2010), then "narrow circle" is no law of nature but merely the stress mode — and the entire dark scenario is conditional, not destiny.

## Reading the map

- **Edge color = confidence:** green evidenced · amber plausible · purple contested
- **Sign = polarity:** solid / **+** = same-direction (more → more) · dashed / **−** = opposite-direction (more → less) · curved ↺ = feedback loop
- **Nodes:** ◇ branch point · ◎ convergence (attractor) · ★ tipping variable · 🔒 locked · ⊙ substrate premise · green border = bright path

The file is data-driven: the `NODES` and `EDGES` objects at the top of the `<script>` block are the single source of truth. Every edge carries `conf` (confidence), `pol` (`+`/`−`), and optionally `loop:true`. A new chain = a few lines there.

---

*Quo Vadimus is a question, not a verdict — it keeps utopia and dystopia open. If you disagree with the map at a concrete node, it has served its purpose.*
