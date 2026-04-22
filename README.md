# Assignments

[![Repo](https://img.shields.io/badge/repo-Andriyichenko%2Fassignments-555)](https://github.com/Andriyichenko/assignments)
![Last Commit](https://img.shields.io/github/last-commit/Andriyichenko/assignments)
![Repo Size](https://img.shields.io/github/repo-size/Andriyichenko/assignments)
![License](https://img.shields.io/github/license/Andriyichenko/assignments)
![LaTeX](https://img.shields.io/badge/LaTeX-TeX%20Live-0f7d5c)

本リポジトリには、コンピュータサイエンスを中心に、基礎数学（TA用）、代数幾何(院)、量子情報理論(院)、情報科学I、Cross-Culture（教養） の課題に関する LaTeX ソースファイルとコンパイル済み PDF が含まれています。

## 基礎数学 (PDFs)

以下の表の「説明」をクリックすると、PDFファイルを直接閲覧できます。

| 課題名 | 説明 |
| :--- | :--- |
| **基礎数学1** | [ε-δ(ε-N)論法による証明の例](Basic_Math/out/japanese_version.pdf) — 数列の極限、極限の四則演算、逆数の極限、局所有界性、単調収束定理 |

## 代数・幾何 (PDFs)

以下の表の「説明」をクリックすると、PDFファイルを直接閲覧できます。

| 課題名 | 説明 |
| :--- | :--- |
| **講義 1** | [ガウスの消去法と置換行列](Algebra-Geometrics/out/lesson_1.pdf) — ピボット選択、上三角化、群の同型 |

## 量子情報理論 (PDFs)

以下の表の「説明」をクリックすると、PDFファイルを直接閲覧できます。

| 課題名 | 説明 |
| :--- | :--- |
| **レポート 1** | [トレースと密度行列の課題](quantum-info-theory/out/YI_Ran_61112600301_report1.pdf) — 基底変換によるトレース不変性と密度行列の条件 |

## ディレクトリ構成

*   **Week 2**: コンピュータの歴史に関するトピック（アラン・チューリング、ARPANET、深層学習など）を扱っています。
*   **情報科学I**: 論理演算や真理値表に関する課題（第10回、第11回）が含まれています。

## 情報科学I (PDFs)

以下の表の「説明」をクリックすると、PDFファイルを直接閲覧できます。

| 課題名 | 説明 |
| :--- | :--- |
| **第2週 課題** | [コンピュータ史に関する課題原本](CS1/week2/out/week2.pdf) |
| **第2週 提出物** | [第2週の学生提出版](CS1/week2/out/YI_Ran_21122200512.pdf) |
| **第10回 課題** | [論理と真理値表](CS1/情報科学I/out/YI_Ran_21122200512_10th.pdf) |
| **第11回 課題** | [論理演算](CS1/情報科学I/out/YI_Ran_21122200512_11th.pdf) |
| **第12回 課題** | [オイラー小道(閉路)の証明](CS1/情報科学I/out/YI_Ran_21122200512_12th.pdf) |
| **第13回 課題** | [オートマトン](CS1/情報科学I/out/YI_Ran_21122200512_13th.pdf) |
| **第14回 課題** | [数論](CS1/情報科学I/out/YI_Ran_21122200512_14th.pdf) |

## Cross-Culture課題 (PDFs)
| 課題名 | 説明 |
| :--- | :--- |
| **Week 11** | [Plan a small performative intervention](Cross-Culture/out/YI_Ran_21122200512_11th.pdf) |
| **Final 1/2** | [Reflective essay on one-to-one performance](Cross-Culture/out/YI_Ran_21122200512_one-to-one-performance.pdf) |
| **Final 2/2** | [Reflective essay on activities around The Window of the Spaceship "In-Between"](Cross-Culture/out/YI_Ran_21122200512_the-window-of-the-spaceship.pdf) |

## コンパイル方法

ソースファイルは `jarticle` ドキュメントクラスを使用したLaTeXで記述されています。再コンパイルするには、日本語処理に対応したLaTeX環境（TeX Liveや`platex`など）が必要です。

**実行コマンド例:**

```bash
cd CS1/week2
platex week2.tex
dvipdfmx week2.dvi
```
---

## CS1 Assignments

This repository contains LaTeX source files and compiled PDF documents for CS1-related coursework, including Basic Math（for TA）, Algebra-Geometrics, Quantum Info Theory, Information Science I, and Cross-Culture.

## Assignment List of Basic Math (PDFs)

Click the description text in the table below to view the PDF files directly:

| Assignment Name | Description |
| :--- | :--- |
| **Basic Math 1** | [ε-δ(ε-N)論法による証明の例](Basic_Math/out/japanese_version.pdf) — sequence limits, arithmetic of limits, reciprocal limits, local boundedness, and the monotone convergence theorem |

## Assignment List of Algebra-Geometrics (PDFs)

Click the description text in the table below to view the PDF files directly:

| Assignment Name | Description |
| :--- | :--- |
| **Lecture 1** | [Gaussian elimination and permutation matrices](Algebra-Geometrics/out/lesson_1.pdf) — pivot selection, upper-triangular reduction, and group isomorphism |

## Assignment List of Quantum Info Theory (PDFs)

Click the description text in the table below to view the PDF files directly:

| Assignment Name | Description |
| :--- | :--- |
| **Report 1** | [Trace and density matrix exercises](quantum-info-theory/out/YI_Ran_61112600301_report1.pdf) — trace invariance under basis change and the Bloch-sphere condition for density matrices |

## Directory Structure

*   **Week 2**: Covers topics related to computer history (e.g., Alan Turing, ARPANET, Deep Learning).
*   **Information Science I**: Contains assignments on logic operations and truth tables (10th and 11th assignments).

## Assignment List of Info Science (PDFs)

Click the description text in the table below to view the PDF files directly:

| Assignment Name | Description |
| :--- | :--- |
| **Week 2 Assignment** | [Original assignment file covering computer history](CS1/week2/out/week2.pdf) |
| **Week 2 Submission** | [Student submission for Week 2](CS1/week2/out/YI_Ran_21122200512.pdf) |
| **10th Assignment** | [Logic and truth tables](CS1/情報科学I/out/YI_Ran_21122200512_10th.pdf) |
| **11th Assignment** | [Logic operations](CS1/情報科学I/out/YI_Ran_21122200512_11th.pdf) |
| **12th Assignment** | [Proof of the existence of an Eulerian path (circuit)](CS1/情報科学I/out/YI_Ran_21122200512_12th.pdf) |
| **13th Assignment** | [Automaton](CS1/情報科学I/out/YI_Ran_21122200512_13th.pdf) |
| **14th Assignment** | [Number Theory](CS1/情報科学I/out/YI_Ran_21122200512_14th.pdf) |

## Assignment List of Cross-Culture (PDFs)
| Assignment Name | Description |
| :--- | :--- |
| **Week 11** | [Plan a small performative intervention](Cross-Culture/out/YI_Ran_21122200512_11th.pdf) |
| **Final 1/2** | [Reflective essay on one-to-one performance](Cross-Culture/out/YI_Ran_21122200512_one-to-one-performance.pdf) |
| **Final 2/2** | [Reflective essay on activities around The Window of the Spaceship "In-Between"](Cross-Culture/out/YI_Ran_21122200512_the-window-of-the-spaceship.pdf) |

## Compilation

The source files are written in LaTeX using the `jarticle` document class. To recompile them, a LaTeX environment capable of handling Japanese text (such as TeX Live with `platex`) is required.

**Example Command:**

```bash
cd CS1/week2
platex week2.tex
dvipdfmx week2.dvi
```

