# Awesome Tech Stacks by Country [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of data on which programming languages and technologies are used in each country, plus local surveys, job boards and conferences.

Every ranking names its source. Where a ranking was calculated from public data, the entry says so.

## Contents

- [Global Data Sources](#global-data-sources)
<!-- toc-end -->

## Global Data Sources

- [Stack Overflow Developer Survey 2025](https://survey.stackoverflow.co/2025/) - Over 49,000 responses from 177 countries covering languages, databases, tools, and AI use; the 2026 edition opened in June 2026 and its results were not yet published as of 2026-09-19.
- [Stack Overflow Survey data archive](https://github.com/StackExchange/Survey/tree/main/packages/archive/2025) - Raw 2025 responses with a `Country` column, which makes per-country language shares computable.
- [JetBrains State of Developer Ecosystem 2025](https://devecosystem-2025.jetbrains.com/) - 24,534 developers from 194 countries and regions; Brazil, Canada, China, France, Germany, India, Japan, South Korea, Spain, the UK, and the US are weighted as separate regions ([methodology](https://lp.jetbrains.com/developer-ecosystem-2025-methedology/)).
- [GitHub Octoverse 2025](https://github.blog/news-insights/octoverse/octoverse-a-new-developer-joins-github-every-second-as-ai-leads-typescript-to-1/) - GitHub activity from September 2024 to August 2025, including developer counts and growth for the top 10 countries and 2030 projections.
- [GitHub Innovation Graph](https://innovationgraph.github.com/) - Quarterly per-economy data since 2020 on developers, repositories, and the number of developers pushing code in each programming language ([CC0 dataset](https://github.com/github/innovationgraph)).
- [Eurostat: ICT specialists in employment](https://ec.europa.eu/eurostat/statistics-explained/index.php?title=ICT_specialists_in_employment) - Official EU statistics on the number and share of ICT specialists in each member state.
- [BCG: Develop the Developers, a Strategic Priority for Africa](https://www.bcg.com/publications/2026/develop-the-developers-a-strategic-priority-for-africa) - March 2026 study based mainly on GitHub usage data, comparing developer counts and growth across African countries.

### How the per-country language bullets were produced

- **Stack Overflow 2025 (computed)**: share of respondents who answered "I am a developer by profession" and listed the language under `LanguageHaveWorkedWith`, from the public 2025 dataset. Only countries with at least 100 such respondents are shown. Stack Overflow counts HTML/CSS, SQL, and Bash/Shell as languages.
- **GitHub Innovation Graph (computed)**: languages ranked by unique developers who pushed code in 2026 Q1 (`languages.csv`, `language_type = programming`), leaving out Shell, Dockerfile, and similar build or config languages.

## Contributing

Contributions are welcome. Open a pull request with a link to the source for any change.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

---

Maintained by [Ali Hesari](https://alihesari.com). Follow on [GitHub](https://github.com/alihesari) and [X](https://x.com/alihesari) for updates.
