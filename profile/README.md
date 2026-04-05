# 🚀 Docs-as-Code Toolkit

Build documentation like software.

Versioned. Reproducible. Automated.

---

## 🎯 What this is

This is not just a collection of repositories.

It’s a **complete Docs-as-Code ecosystem** designed to:

* eliminate "works on my machine"
* unify tooling across local & CI environments
* enable structured, maintainable architecture documentation
* treat documentation as a **first-class artifact**

---

## 🧩 Components

### 🔧 Infrastructure

* **docs-toolbox**
  Reproducible Docker environment with all required tools
  → Asciidoctor, Pandoc, Graphviz, Fonts

---

### 🧠 Automation

* **doc-generators** *(work in progress)*
  Generate dynamic content:

  * cross-links
  * traceability
  * architecture views

---

### 🎨 Presentation

* **asciidoc-style**
  Reusable styling for:

  * websites
  * architecture docs
  * CVs

---

### 🌐 Example / Showcase

* **profile**
  Real-world usage:

  * personal website
  * CV generation
  * architecture documentation

---

## 🧭 Philosophy

> Write once. Publish everywhere.
> Keep it simple. Make it reproducible.

---

## 🚀 Getting started

Use the toolbox:

```bash
docker run --rm \
  -v $(pwd):/app \
  -w /app \
  ghcr.io/<your-org>/docs-toolbox:latest \
  ./gradlew buildSite
```

---

## 🤝 Why this matters

Documentation is often:

* outdated
* inconsistent
* hard to maintain

This approach turns it into:

✔ versioned
✔ testable
✔ reproducible
✔ automatable

---

## 👤 Author

Created by [Dieter Baier](https://gibhub.com/dieterbaier)
Software Architect · Docs-as-Code enthusiast
