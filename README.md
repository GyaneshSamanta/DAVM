# Data Analysis & Visualization Methods (DAVM)

> **A semester-long journey through the language of data — from raw CSVs to executive dashboards.**

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?logo=tableau&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?logo=microsoft-excel&logoColor=white)

## About

- **What:** A complete coursework archive for the Data Analysis and Visualization Methods (DAVM) module — datasets, Tableau workbooks, Power BI reports, case studies, and exam prep.
- **Who:** Authored by Gyanesh Samanta as part of his postgraduate analytics curriculum.
- **When:** October 2025 through March 2026 (one full academic term of weekly sessions).
- **Where:** Built in classroom labs and at home — submissions land here every session.
- **Why:** To build fluency with the tooling that turns spreadsheets into stories, and to keep an organized record of every chart, dashboard, and case I tackled along the way.

## The Story

DAVM started the way most analytics classes do: a folder of CSVs, a blinking cursor, and the question *"so what does this data actually mean?"*. Week one was Superstore sales. Week two was hospital visit logs. By week ten the prompts had grown into multi-source case studies — wine quality, vacation rentals, retail performance — each one demanding a different visual grammar.

This repo is the working notebook that held it all together. The `Workbooks/` folder traces the Tableau learning curve from `Session 2.twb` (basic bars and lines) through `davm 6.1.twbx` (parameterized dashboards with calculated fields). The `PowerBI/` folder captures the pivot to Microsoft's stack mid-semester. `Group Case Study/` and `Group Project/` are the moments when individual practice turned into team deliverables.

What you'll find here isn't polished portfolio work — it's the messy, iterative truth of learning to think visually about data.

---

## Tech Stack

| Layer | Tools |
|-------|-------|
| Visualization | Tableau Desktop, Microsoft Power BI |
| Spreadsheet analysis | Microsoft Excel |
| Data formats | CSV, XLS/XLSX, TWB/TWBX, PBIX |

## Repo Structure

```
DAVM/
├── DAVM_Class Files/        # Lecture handouts and reference material
├── Dataset/                 # Raw CSVs and Excel sources for every session
│   ├── Case Study 4/
│   ├── Case study 2/
│   └── PowerBI Dataset/
├── PowerBI/                 # .pbix dashboards (Case Study 2, Session 1)
├── Workbooks/               # Tableau .twb and .twbx workbooks (Sessions 2-20)
├── Group Case Study/        # UV8620 case (Excel)
├── Group Project/           # Tableau-based group submission with dataset
└── Previous Year Solution/  # Reference solutions for exam prep
```

## Getting Started

You'll need either **Tableau Desktop / Tableau Public** or **Microsoft Power BI Desktop** depending on which artifact you want to open.

```bash
# Clone the repo
git clone https://github.com/GyaneshSamanta/DAVM.git
cd DAVM
```

- Open `Workbooks/davm 6.1.twbx` in Tableau — packaged workbooks ship with their data.
- Open `PowerBI/Case Study 2.pbix` in Power BI Desktop.
- Datasets live under `Dataset/` if you want to build from scratch.

## Contributing

This is a personal coursework archive, so PRs aren't really the workflow — but if you're a fellow student and you spot a calculation error, open an issue and let's talk.

## License

Released under the terms in [LICENSE](LICENSE).

## Credits

- **Author:** [Gyanesh Samanta](https://github.com/GyaneshSamanta)
- **Course:** Data Analysis and Visualization Methods
- **Datasets:** Tableau Sample Superstore, UVA Darden case UV8620, and assorted instructor-provided sources.
