<div align="center">

# 🤝 Contributing

**Thanks for helping make the Periodic Table better!**
This is a single-file project, so contributing is quick and painless.

</div>

## 🧭 Ways to help

| | |
|---|---|
| 🐛 **Report a bug** | [Open a bug report](../../issues/new?template=bug_report.md) |
| 💡 **Suggest a feature** | [Open a feature request](../../issues/new?template=feature_request.md) |
| 🧪 **Fix element data** | Correct a value and cite a source in your PR |
| 🎨 **Polish the UI** | Animations, accessibility, mobile tweaks |
| ⭐ **Star the repo** | The easiest contribution of all |

## 🚀 Workflow

1. **Fork** the repository
2. **Create a branch**: `git checkout -b fix/tooltip-clipping`
3. **Edit** `periodic-table.html` directly
4. **Test** — open the file in a browser, no build step needed
5. **Commit** with a clear message (e.g. `fix: keep tooltip inside viewport`)
6. **Open a Pull Request** describing what changed and why

## ✅ Guidelines

- Keep it **one self-contained HTML file** — no new build tooling or dependencies without discussing it first
- Match the existing style: **vanilla JS**, no frameworks
- If you touch layout, touch input or 3D, test on **at least one desktop and one mobile browser**
- New views or quiz questions are welcome — add a view to the `VIEWS` object, or a question type to `makeQuestion()`
- Keep element data **accurate** — cite a source (IUPAC, NIST, PubChem…) when correcting properties
- Keep pull requests **focused** — one change per PR is easiest to review

## 🐞 Reporting bugs

Please include:

- A clear description of the problem
- Steps to reproduce
- Browser, OS and device
- A screenshot or screen recording, if relevant

## 💬 Code of Conduct

Participation is governed by the [Code of Conduct](CODE_OF_CONDUCT.md). In short: be kind and constructive.

<div align="center">

<sub>A <b>Rajdip Dhar</b> project · MIT licensed</sub>

</div>
