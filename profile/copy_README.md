# 🦉 Open Workflow Library (OWL)

**Welcome to OWL — the Open Workflow Library.**
Our mission is to make trustworthy, production‑ready bioinformatics & scientific pipelines *easy to find, easy to reuse, and easy to improve*.

## 🚀 What is OWL?

OWL is a community‑curated catalogue of open‑source workflows written in standards such as **CWL, Nextflow, WDL, Snakemake** and others. Every pipeline in the library is:

* **Validated** – automatically tested on reference data sets.
* **Versioned** – tagged releases with full provenance metadata.
* **Reproducible** – bundled with container images and exact software specs.

## 🤖 Smarter CI/CD

Behind the scenes OWL runs a continuous integration system that blends conventional tests with **generative‑AI–assisted refactoring**.
After each pull request OWL:

1. Spins up test jobs to ensure the workflow still produces expected results.
2. Invokes AI agents to suggest clearer parameter names, tighter resource limits, or more portable patterns.
3. Opens automated improvement PRs that contributors can accept, tweak, or decline.

The goal is fewer bugs, cleaner code, and steadily improving performance without extra burden on maintainers.

## 🛠️ Meet **OWLkit**

OWLkit is the companion CLI / SDK that lets you work with the library from your laptop or CI server.

| Capability     | What it does                                             |
| -------------- | -------------------------------------------------------- |
| `owl init`     | Scaffold a new workflow repo with the recommended layout |
| `owl validate` | Run schema linting and test datasets locally             |
| `owl pack`     | Build a reproducible container bundle                    |
| `owl submit`   | Create a signed metadata archive & open a PR to OWL      |
| `owl search`   | Query the catalogue by keyword, modality, organism, etc. |
| `owl upgrade`  | Pull AI‑generated refactor suggestions for your workflow |

> **Why use OWLkit?**
> • Save hours on boilerplate.
> • Catch schema errors before CI.
> • Keep your pipelines reproducible & discoverable.

Install with:

```bash
pip install owlkit            # Python ≥3.9
# or
curl -sSL https://owl.promptable.ai/install.sh | bash
```

## 🌱 How to Contribute

1. **Fork** the workflow template or start with `owl init`.
2. **Add** reference tests & containers.
3. **Run** `owl validate` until everything passes.
4. **Open** a pull request to this org; our CI & AI helpers will take it from there!
5. **Join** the discussion on GitHub Discussions.

Contributions of all sizes are welcome—new pipelines, documentation fixes, or feature ideas.

## 🔭 Roadmap Highlights

* Expanded human genomics test datasets
* Benchmark suite for machine‑learning pipelines
* Plugin system for custom linting rules
* Public dashboard of CI metrics & provenance graphs

## 📚 Useful Links

* 🌐 Library portal: [https://owl.promptable.ai](https://owl.promptable.ai)
* 📦 OWLkit releases: [https://pypi.org/project/owlkit/](https://pypi.org/project/owlkit/)
* 📝 Contribution guide: [`CONTRIBUTING.md`](./CONTRIBUTING.md)
* 📄 Code of Conduct: [`CODE_OF_CONDUCT.md`](./CODE_OF_CONDUCT.md)

---

*OWL is built by and for the research community. Your expertise keeps it vibrant—jump in and help us build the world’s most reliable collection of open scientific workflows!*
