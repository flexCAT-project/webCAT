# WebCAT

Available at <https://flexcat-project.github.io/webCAT/>

webCAT brings computerized adaptive testing (CAT) to [Qualtrics](https://www.qualtrics.com/) surveys and tests. This repository contains the Quarto website that guides users through setting up their CAT step by step. The adaptive engine runs in a separate repository and is built on the R packages **mirt** [@Chalmers_2012_mirt] and **mirtCAT** [@Chalmers_2016_mirtCAT].


## What the site does

-   **Home**: generate an access token (and optionally receive it by e-mail).
-   **Procedure**: four steps to set up a test.
    -   Step 0: download an item bank template (CSV) .
    -   Step 1: upload the completed item bank.
    -   Step 2: choose the IRT model (Rasch, 2PL, GRM, GPCM) and a fixed- or variable-length CAT.
    -   Step 3: connect a Qualtrics survey with the provided JavaScript snippets.
-   **Results**: download respondents' responses, θ estimates and standard errors as CSV.

Two ready-made example item banks are included in the tutorial: **TCAT** (36 dichotomous English–Dutch vocabulary items, 2PL) and **PPSE** (19 polytomous PROMIS stress items, graded response model).

## Feedback

webCAT is in beta. If something doesn't work, please [open an issue](https://github.com/flexcat-project/webCAT/issues).

## License

MIT. See [LICENSE](LICENSE).
