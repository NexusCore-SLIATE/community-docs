# 📜 Code & Version Control Engineering Standards

To build a professional and scalable ecosystem, we write clean, readable, and highly maintainable systems. These technical guidelines apply to all development tracks.

## 🎨 JavaScript, HTML, & CSS Baselines
* **Vanilla First:** Focus on semantic HTML5 structures and vanilla ES6+ modern native features before suggesting dependencies or external utilities.
* **Formatting Consistency:** Use 2 spaces for indentation. Keep your naming clean:
  * `camelCase` for variable and function names.
  * `PascalCase` for classes and component modules.
  * `kebab-case` for file assets, folder directories, and CSS classes.
* **Avoid Magic Numbers:** Extract obscure configuration parameters, timing constants, or values into clearly named variable definitions at the top of your scripts.

## 🌿 Git & Branch Naming Conventions
Our repositories enforce standard prefix branching rules. Always branch off of `main`:

| Branch Prefix | Used For | Example |
| :--- | :--- | :--- |
| `feature/` | Introducing new features or design components | `feature/auth-validator` |
| `bugfix/` | Resolving an open issue or structural bug | `bugfix/mobile-nav-leak` |
| `docs/` | Updating documentation, comments, or wikis | `docs/setup-instructions` |
| `refactor/` | Cleaning up working code without adding features | `refactor/optimize-loops` |

## 📝 Commit Messages Rulebook
We use strict **Conventional Commits** (`type: description`). This makes tracking our codebase changes scannable:

* ✅ `feat: add dynamic network routing table logic`
* ✅ `fix: resolve zero-padding calculation crash in UI grid`
* ✅ `docs: write instructions for mounting cyber lab image`
* ❌ `bad commit: fixed some stuff on the landing page`
* ❌ `bad commit: working copy`
