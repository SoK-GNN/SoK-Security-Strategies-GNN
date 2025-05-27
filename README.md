# SoK: Security Strategies for Graph Neural Networks (Companion Index)

Companion index for the paper **“SoK: Security Strategies for Graph Neural Networks”**, cataloguing adversarial attack & defense methods, with links to publications, downstream tasks, and open-source code.

---

## 📖 Table of Contents

- [Attacks](ATTACKS.md)
- [Defenses](DEFENSES.md)
- [Template](templates/paper_entry_template.md)

---

## 🚀 Quickstart

1. **Browse**
   - **`ATTACKS.md`** — Attack papers index
   - **`DEFENSES.md`** — Defense papers index
   - **`Adjustments.xlsx`** — Excel sheet containing some of the installation steps we performed that were not included in the codebases.

2. **Add a new entry**
   1. Copy the row format from `templates/paper_entry_template.md`.
   2. Fill in:
      ```markdown
      | [Paper Title](https://doi.org/…) | 2025 | Node classification | [Link](https://github.com/…) |
      ```
   3. Commit and open a PR.

---

## 🤝 Contributing Guidelines

- **Accuracy**: Verify titles, years, and URLs.
- **Downstream Task**: Provide a concise description.
- **Code Links**: Use `[Link](URL)`; use `N/A` if code is unavailable.
- **Style**: Maintain consistent table formatting.
- **Review**: All PRs are reviewed for formatting and link validity.

---

## 📚 Project Structure

```
SoK-GNN-Security-Atlas/
├── README.md
├── ATTACKS.md
├── DEFENSES.md
└── templates/
    └── paper_entry_template.md
```

---

## ⚖️ License

Distributed under the MIT License. See [LICENSE](LICENSE) for details.
