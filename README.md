# Masterclass: AI/ML Benchmarking

CMS masterclass talk, **26 October 2026** — Ben Hawks, Fermilab.

An interactive, browser-based talk on scientific AI/ML benchmarking: what makes a good benchmark, where HEP's existing benchmarks stand when scored, and the reasoning and technique behind benchmarking well (starting from the decision, honest baselines, metrics at the working point, splits and leakage, uncertainties, reading a result critically).

- **Live talk:** <https://ben-hawks.github.io/cms-masterclass-benchmarking/>
- `index.html` — the whole talk, one self-contained file (figures embedded). Open it in any modern browser; no build step.
- `masterclass-benchmarking.pdf` — static backup with searchable text and clickable links: every scene at its final step, 27 main-flow pages then 9 backups.
- Keys: → / space / click to advance, ← back, **O** overview (incl. backups), **H** speaker notes + timer, **D** theme, **F** fullscreen, **?** help. Deep links: `#ratings`, `#def.3`.
- Main flow: 27 scenes, ~27 min of budget. Backups: three kinds of reader, prior work, ontology overview, computing motifs, workload clustering, benchmark card, repository layout, glossary, credits.
- Every technical term is defined in a "terms" footer on the slide where it first appears; the full list is in the glossary backup.

## Credits

- **Presentation design and scene engine** adapted from Andrzej Novak's CMS internal masterclass talk on the JFC paper (22 Sep 2026): <https://github.com/jfc-mit/jfc-talk> (branch `cms-masterclass-2026-09-22`). That deck is itself styled after the hcc-kappac Florence talk and <https://www.danielmurnane.com/ETH-Agentic-AI-for-Collider-Physics/>. The paper theme, colour tokens, mono crumb/counter chrome, the part outline that returns at the head of each part, and the scene/step flow follow it. The engine here is a re-implementation, not a copy of its code.
- **Benchmark definition, rating rubric, Table II data (74 tasks), Figs. 1 and 3**: B. Hawks, G. von Laszewski, M. D. Sinclair, M. Colombo, S. Venkataraman, R. Jain, Y. Jiang, N. Tran, G. Fox, "An MLCommons Scientific Benchmarks Ontology", arXiv:2511.05614. Companion site: <https://mlcommons-science.github.io/benchmark/>.
- **Part IV examples** (AXESS worked example and leaderboard, baselines, one scorer for every model, lessons) adapted from B. Hawks, "Benchmarking-driven model development", tutorial session, 15 October 2026.
- **Benchmark names** (Part III table and hover tooltips) are taken from the ontology's source data, <https://github.com/mlcommons-science/benchmark> (`source/benchmarks*.yaml`), matched to Table II by domain, motif and rating; three long names are shortened. FastML Science Benchmarks itself is not an ontology entry: three of its tasks are (Jet Classification, Irregular Sensor Data Compression, Beam Control), and it appears only as prior work.
- **Typeface**: EB Garamond (SIL Open Font License), via Google Fonts.

## Illustrative content

These are drawn for teaching and are not measured results: the traditional vs. AI-enhanced pipeline numbers, the latency–accuracy Pareto plot, the rejection-vs-efficiency curves, the leaderboard with uncertainties, the CMS L1-trigger example, the HEP examples on the five-element and computing-motif slides, and the "dataset + paper" preset in the scoring exercise. Each is labelled illustrative on its slide.
