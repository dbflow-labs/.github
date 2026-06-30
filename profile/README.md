# DBFlow Labs

**Model-first approval workflow engine for Laravel & Filament.**

DBFlow Labs is an engineering-first organization building approval workflow infrastructure for the modern Laravel ecosystem — instances, tasks, reject strategies, and audit logs attached to Eloquent models, without a heavyweight BPM platform.

We treat workflow logic as core infrastructure: robust, observable, strictly versioned, and testable — not scattered ad-hoc business code.

> **Alpha notice:** Core and Filament packages are in active alpha (`v0.1.0-alpha.1`). Public APIs and schema details may change before v1.0.0. Pin exact tags for production experiments.

---

### Our Projects

Our ecosystem follows an **Open-Core** strategy: a solid MIT-licensed runtime foundation, standard Filament UI integration, and commercial visual authoring for advanced requirements.

| Project | Composer | Description | Role | Status |
| :--- | :--- | :--- | :--- | :--- |
| [**dbflow-core**](https://github.com/dbflow-labs/dbflow-core) | `dbflowlabs/core` | Model-first workflow runtime: definitions, instances, tasks, approvals, reject strategies, and append-only audit logs. | Engine | Alpha · MIT |
| [**dbflow-filament**](https://github.com/dbflow-labs/dbflow-filament) | `dbflowlabs/filament` | Standard Filament integration: My Tasks, workflow instances, audit timelines, and form-based definition management. | Interface | Alpha · MIT |
| [**DBFlow Pro**](https://dbflow.dev/) | `dbflowlabs/filament-pro` | Visual workflow builder and advanced authoring capabilities. | Commercial | Early Access |

DBFlow is **not** a BPMN server, a Zapier clone, or a general low-code automation platform. It focuses on approval workflows attached to Laravel business models.

---

### Engineering Philosophy

We design our software based on the following engineering principles:

* **Deterministic Integrity**: Workflow execution must be predictable. Strict version isolation ensures definitions and running instances never drift.
* **Zero-Bloat Minimalist**: We reject the complexity of traditional BPMN standards. Atomic nodes and directed graphs solve problems without creating them.
* **Concurrency First**: Built-in state locking and transaction safety handle high-frequency approval operations without double-action races.
* **Infrastructure over Implementation**: Simple contracts and traits integrate with host domain logic, keeping business models clean and independent.

---

### Resources

* **Official Website**: [https://dbflow.dev](https://dbflow.dev) — product overview, architecture, documentation, and licensing.
* **Documentation**: [https://dbflow.dev](https://dbflow.dev) and each repository's README.
* **Live Demo**: Available from the official website — no install required.
* **Support**: For enterprise inquiries, architectural consulting, or commercial licensing, contact [hello@dbflow.dev](mailto:hello@dbflow.dev) or visit [dbflow.dev](https://dbflow.dev).

---

### Community & Contribution

We value engineering quality over quantity.

Before submitting issues or pull requests, read [CONTRIBUTING.md](https://github.com/dbflow-labs/.github/blob/main/.github/CONTRIBUTING.md). Use the provided issue and pull request templates. Open bug reports only for confirmed, reproducible defects. For usage questions, consult [dbflow.dev](https://dbflow.dev) documentation first.

*DBFlow Labs is a neutral, independent developer initiative.*
