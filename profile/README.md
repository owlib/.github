# 🦉 Workflow Library

**A library of observable, composable, and promptable scientific workflows.**

The Workflow Library is a curated collection of reproducible, self-describing analytics and scientific software stacks. Each stack is built for clarity, reusability, and integration into both human- and machine-driven research pipelines.

This library serves as a resource for researchers, engineers, and tool developers who want to:

* Build transparent, pipeable data transformation pipelines
* Package workflows as clean Python modules with promptable interfaces
* Emit interoperable artifacts like CWL, JSON, QMD, or summaries
* Enable prompt-driven orchestration, testability, and documentation

---

## 🔍 What is an Observable Workflow Stack?

An **Observable Workflow Stack** (OWS) is a self-contained Python package that includes:

* **🧠 Analytics logic** in tidy, pipeable, and modular functions (often using `polars`)
* **📜 Prompt templates** for natural language summarization or LLM integration
* **📤 Emitters** to export components as CWL, Markdown, or reports
* **🧪 Smoke tests** and example data for validation and onboarding
* **🧱 Structured layout** that supports internal reuse and external publication
* **🕵️ Self-description**, via a `describe_stack()` method and metadata formats

Each stack is installable, testable, observable, and extendable.

---

## 📁 Example Stack Structure

```bash
my-stack/
├── pyproject.toml
├── README.md
├── src/
│   └── my_stack/
│       ├── __init__.py
│       ├── logic.py
│       ├── prompts/
│       │   └── plan.prompt.txt
│       ├── emitters/
│       │   └── cwl.py
├── test/
│   └── test_smoke.py
└── Dockerfile (optional)
```

---

## 📦 What’s Inside This GitHub Org

* 🔬 Domain-specific analysis stacks (e.g., metrics, omics, QA/QC)
* 🧰 Shared emitters and utilities (e.g., CWL generation, Quarto exports)
* 💡 Examples and templates to help you scaffold your own Observable Workflow Stack
* 📖 Documentation (coming soon to [workflowlibrary.org](https://workflowlibrary.org))

---

## 💡 Why “Observable”?

* You can **inspect** what each stack does and how
* You can **query or prompt** it for summaries or usage
* You can **emit structured output** to use downstream
* You can **trust its structure** to be consistent across stacks

Observable means: **self-describing, testable, and ready to integrate.**

---

## 🚀 Get Started

Want to make your own Observable Workflow Stack?

* Check out [`stack-template`](https://github.com/workflow-library/stack-template)
* Follow the conventions in `describe_stack()`, `emitters/`, and `prompts/`
* Keep it reproducible, readable, and promptable

---

## 📫 Contact

* 🌐 Website: [workflowlibrary.org](https://workflowlibrary.org)
* 📧 Email: [hello@workflowlibrary.org](mailto:hello@workflowlibrary.org)

Want to contribute a stack or suggest a convention? Reach out or open an issue!
