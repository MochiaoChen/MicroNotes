# Intermediate Microeconomics Notes

![Language](https://img.shields.io/badge/language-English-blue.svg) ![LaTeX](https://img.shields.io/badge/Made%20with-LaTeX-green.svg) ![UIBE](https://img.shields.io/badge/School-UIBE-red.svg)

## Introduction

This repository contains my personal lecture notes for the **Intermediate Microeconomics** course at the **University of International Business and Economics (UIBE)**.

These notes are written entirely in **English** and typeset using **$\LaTeX$**. They are specifically curated for the curriculum of the **Hongru Financial Talents Experimental Class** within the School of Finance.

## Course Information

- **University**: University of International Business and Economics (UIBE)
- **School**: China School of Finance
- **Program**: Hongru Financial Talents Experimental Class
- **Instructor**: Prof. Zhang Haiyang
- **Textbook**: *Intermediate Microeconomics: A Modern Approach* by Hal R. Varian

## Repository Structure

The project is organized as follows:

- **`main.tex`**: The root $\LaTeX$ file that compiles the entire document.
- **`chapters/`**: Contains separate `.tex` files for each chapter or topic (e.g., Consumer Theory, Production, Market Structure).
- **`figures/`**: Contains images and TikZ diagrams used in the notes.
- **`ref.bib`**: (If applicable) Bibliography file.

## Features

- **Comprehensive Coverage**: Notes are based on Prof. Zhang's lectures and Varian's textbook.
- **High-Quality Typesetting**: Features clear mathematical definitions, theorems, and proofs formatted in $\LaTeX$.
- **Modular Design**: Chapters are managed in separate files within the `chapters/` directory for easier editing and maintenance.

## How to Compile

To build the PDF from the source code, you will need a TeX distribution (such as TeX Live or MiKTeX).

1. Clone the repository:
   ```bash
   git clone [https://github.com/MochiaoChen/MicroNotes.git](https://github.com/MochiaoChen/MicroNotes.git)

2.  Navigate to the project directory:

    ```bash
    cd MicroNotes
    ```

3.  Compile the `main.tex` file. It is recommended to use `xelatex` or `pdflatex`:

    ```bash
        xelatex main.tex && makeindex main && xelatex main.tex && xelatex main.tex
    ```

## Disclaimer

These are unofficial student notes created for educational purposes. While I strive for accuracy, there may be errors or typos. These notes should be used as a supplement to, not a substitute for, official course materials.

## Contributing

Contributions are welcome\! If you spot an error in the equations or text, feel free to:

1.  Open an **Issue** to report the problem.
2.  Submit a **Pull Request** to fix it directly.

-----

**Author**: Mochiao Chen
**Last Updated**: 2025.12
