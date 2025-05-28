# 🦉 Open Workflow Library

Welcome to the **Open Workflow Library** (OWL), home of community-driven specs, tooling, and “agentic” workflows for bioinformatics and beyond.

---

## 📖 What Is OWL?

The Open Workflow Library (OWL) is a collaborative, open-source organization dedicated to:

* **Standardizing** YAML-based workflow definitions (tools, agents, goals, roles).
* **Empowering** domain-specific agents (DSAs) to orchestrate complex pipelines via simple, human-readable specs.
* **Providing** modular tooling (CLI, runtime, catalogs) to build, test, and deploy your workflows.
* **Cultivating** a vibrant community around “promptable” agentic workflows.

---

## 🚀 Quick Start

1. **Explore our repos**

   * **[`owl-spec`](https://github.com/owlib/owl-spec)**:
     YAML schemas & canonical examples.
   * **[`owlkit`](https://github.com/owlib/owlkit)**:
     CLI to scaffold, validate, and run OWL specs.
   * **[`owl-core`](https://github.com/owlib/owl-core)**:
     Runtime engine for agentic execution.
   * **[`owl-catalog`](https://github.com/owlib/owl-catalog)**:
     Curated library of community-contributed workflows & agents.
   * **Domain-specific agents** (e.g., [`rnaseq-agent`](https://github.com/owlib/rnaseq-agent), [`sv-agent`](https://github.com/owlib/sv-agent`), …)

2. **Install `owlkit`**

   ```bash
   pip install owlkit
   # or
   npm install -g @owlib/owlkit
   ```

3. **Create a new workflow**

   ```bash
   owlkit init my-project
   cd my-project
   owlkit validate spec.yaml
   owlkit run spec.yaml
   ```

4. **Browse the catalog**

   ```bash
   owlkit catalog list
   owlkit catalog install rnaseq-agent
   ```

---

## 📂 Org Structure

```
owlib/
├─ owl-spec/       # YAML schema definitions & documentation
├─ owlkit/         # Command‐line tooling (scaffold, lint, run)
├─ owl-core/       # Agentic runtime engine
├─ owl-catalog/    # Community “card catalog” of workflows & agents
├─ <modality>-agent/  # Domain-specific agent repos (RNA-seq, SV, etc.)
└─ README.md       # This overview
```

---

## 🤝 Contributing

We welcome contributions of all kinds! Please:

1. **Fork** the repo you’d like to improve.
2. **Create** a feature branch:

   ```bash
   git checkout -b feature/awesome-agent
   ```
3. **Commit** your changes & open a PR against `main`.
4. **Discuss** with maintainers & address review feedback.
5. **Celebrate** when your PR is merged! 🎉

Be sure to read the [`CONTRIBUTING.md`](https://github.com/owlib/owl-spec/blob/main/CONTRIBUTING.md) in each repo for repo-specific guidelines.

---

## 📣 Get Involved

* **Join our community** on [GitHub Discussions](https://github.com/owlib/owl-spec/discussions)
* **Chat with us** on [Slack](https://owlib-slack-invite.example.com)
* **Follow updates** via [Twitter](https://twitter.com/owlib_org) or [LinkedIn](https://linkedin.com/company/owlib)

---

## 📄 License

All OWL repos are licensed under [Apache 2.0](https://github.com/owlib/owl-spec/blob/main/LICENSE). See individual projects for details.

---

> **Open Workflow Library** — Empowering your pipelines with agentic intelligence.
> Learn more at [owlib.org](https://owlib.org)
