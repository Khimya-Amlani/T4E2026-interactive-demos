# Interactive Computational Demonstrations for Engineering Mathematics

Supplementary material for the paper:

> Amlani, K.: *Interactive Computational Demonstrations for Enhancing Conceptual Understanding in Engineering Mathematics: An Experience Report.* T4E 2026 (submission 32).

**Author:** Dr. Khimya Amlani ([ORCID 0000-0003-0034-2388](https://orcid.org/0000-0003-0034-2388)), First Year Engineering, Vidyalankar Institute of Technology, Mumbai, India

## Run the demonstrations

Each demonstration is a single HTML file. Open it in any modern browser. No installation, server or licence is needed.

| Demonstration | Topic | Run online |
|---|---|---|
| Laplace transform: pole-zero explorer | Poles, stability and step response of K/(s+a) and second-order systems; f(t) ↔ F(s) calculator | [laplace_demo.html](https://khimya-amlani.github.io/T4E2026-interactive-demos/laplace_demo.html) |
| SVD image compression | Rank-K approximation of a 128×128 image; storage versus quality | [svd_demo.html](https://khimya-amlani.github.io/T4E2026-interactive-demos/svd_demo.html) |
| Active noise cancellation | Vector addition: s(t) + n(t) + (−n(t)) = s(t), with a 3D view | [ANC-Project.html](https://khimya-amlani.github.io/T4E2026-interactive-demos/ANC-Project.html) |

The Laplace demo works offline. The ANC demo loads its 3D library (three.js) from the internet, and the SVD demo loads web fonts, so both need a connection for the full display.

The ANC demonstration was developed by Harsh Jaiswal under the guidance of Dr. Khimya Amlani.

## Data

`T4E32_anonymised_data.xlsx` contains the anonymised evaluation data reported in the paper:

- **Quiz_responses / Quiz_items / Quiz_summary**: vector-basics quiz (10 multiple-choice items), Division B, 26 March 2026, 64 of 75 students
- **Topic_list**: the ten suggested mini-project topics (Assignment 10)
- **Projects / Projects_summary**: all 29 mini-project uploads (18–30 April 2026), with repeat uploads flagged, leaving 26 projects
- **Paper_check**: every number reported in the paper, recalculated from the data
- **Data_dictionary**: the meaning of every column

All results are formulas, so they can be checked in Excel or LibreOffice.

**Anonymisation:** names, e-mail addresses, roll numbers and submission links have been removed. Students are identified only by codes (S01–S64) and projects by division and upload order (A-01…A-17, B-01…B-12). The original records are held by the author and can be shown to the programme chairs on request.

**Not included:** Laplace worksheet answers (discussed orally in class, not kept), instructor observation notes, and groups that presented without uploading.

## Licence

Code and data are released under the [Creative Commons Attribution 4.0 International licence (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). You may reuse and adapt them with credit.

## How to cite

Amlani, K.: Interactive computational demonstrations and anonymised data for "Interactive Computational Demonstrations for Enhancing Conceptual Understanding in Engineering Mathematics" (2026). https://github.com/Khimya-Amlani/T4E2026-interactive-demos
