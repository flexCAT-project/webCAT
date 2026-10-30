# WebCAT

webCAT brings Computerized Adaptive Testing (CAT) to [Qualtrics](https://www.qualtrics.com/) surveys and tests. This repository holds the Quarto website where users set up their adaptive test step by step. The adaptive engine itself runs in the companion [q-cats](https://github.com/flexcat-project/q-cats) API (R / plumber / `mirtCAT`).

## What the site does

- **Home**: generate an access token (and optionally receive it by e-mail).
- **Procedure**: four steps to set up a test.
  - Step 0: download an item bank template (CSV).
  - Step 1: upload the completed item bank.
  - Step 2: choose the IRT model (Rasch, 2PL, GRM, GPCM) and a fixed- or variable-length CAT.
  - Step 3: connect a Qualtrics survey with the provided JavaScript snippets.
- **Results**: download respondents' responses, θ estimates and standard errors as CSV.

Two ready-made example item banks are included in the tutorial: **TCAT** (36 dichotomous English–Dutch vocabulary items, 2PL) and **PPSE** (19 polytomous PROMIS stress items, graded response model).

## Feedback

webCAT is in beta. If something doesn't work, please [open an issue](https://github.com/flexcat-project/webCAT/issues).

## License

MIT. See [LICENSE](LICENSE).