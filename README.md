# AP Chemistry

Self-contained, interactive study pages for AP Chemistry. Each page is a single HTML file with no build step and no dependencies to install — open it in a browser and it works.

**Live site:** https://smartasp.github.io/ap-chemistry/

## Contents

| Page | Topics |
|---|---|
| [Test 1 — Practice Set & Reference](ap-chem-test-1-practice.html) | Significant figures · Percent composition · Mole calculations · Empirical & molecular formulas · Net ionic equations · Alloys · Mass spectrometry · Labs: unknown chloride, hydrate of a salt |

## What's in a practice page

Each page is organized into five tabs:

- **Review Sheet** — the rules, formulas, and worked shapes for every topic, plus the mistakes that most often cost points.
- **Practice** — problems grouped by topic, each with a full step-by-step solution hidden behind a reveal button so you can work it on paper first.
- **Flashcards** — shuffle-able decks for the pure-memorization material: polyatomic ions, solubility rules, strong vs. weak electrolytes, formulas, alloys, and lab procedure.
- **Lab Review** — procedure with the reasoning behind each step, the full calculation, and an error-analysis table giving the direction of error for each common mistake.
- **Final Check** — a self-assessment checklist covering every skill on the test.

A light/dark toggle sits in the navigation bar; pages open in dark mode.

## Technical notes

- Each page is a **single HTML file** — all CSS and JavaScript are inline.
- Math and chemical formulas are typeset with [KaTeX](https://katex.org/) plus the [mhchem](https://mhchem.github.io/MathJax-mhchem/) extension, loaded from a CDN. **An internet connection is needed the first time you open a page** for equations to render.
- No cookies, no analytics, no storage. Checkbox and flashcard state lives in memory only and resets on reload.
- Every numeric answer has been recomputed programmatically and reviewed for correctness and significant figures.

## Local use

Clone the repo and open any `.html` file directly in a browser:

```bash
git clone https://github.com/smartasp/ap-chemistry.git
cd ap-chemistry
open index.html          # macOS
# xdg-open index.html    # Linux
# start index.html       # Windows
```

## Contributing

Corrections are welcome — chemistry errors especially. Open an issue or a pull request describing the problem number and what should change.

## License

Released under the MIT License. See [LICENSE](LICENSE).
