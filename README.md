# CS1 Assignments

[![Repo](https://img.shields.io/badge/repo-Andriyichenko%2Fassignments-555)](https://github.com/Andriyichenko/assignments)
![Last Commit](https://img.shields.io/github/last-commit/Andriyichenko/assignments)
![Repo Size](https://img.shields.io/github/repo-size/Andriyichenko/assignments)
![License](https://img.shields.io/github/license/Andriyichenko/assignments)
![LaTeX](https://img.shields.io/badge/LaTeX-TeX%20Live-0f7d5c)

This repository contains LaTeX source files and compiled PDF documents for the Computer Science 1 (CS1) course.

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

## Assignment List of Cross-Culture (PDFs)
| Assignment Name | Description |
| :--- | :--- |
| **Week 11** | [Plan a small performative intervention](CS1/Cross-Culture/out/YI_Ran_21122200512_11th.pdf) |

## Compilation

The source files are written in LaTeX using the `jarticle` document class. To recompile them, a LaTeX environment capable of handling Japanese text (such as TeX Live with `platex`) is required.

**Example Command:**

```bash
cd CS1/week2
platex week2.tex
dvipdfmx week2.dvi
```

---

# CS1 課題集

本リポジトリには、コンピュータサイエンス入門 (CS1) コースの課題に関するLaTeXソースファイルおよびコンパイル済みのPDFドキュメントが含まれています。

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

## Cross-Culture課題 (PDFs)
| 課題名 | 説明 |
| :--- | :--- |
| **Week 11** | [Plan a small performative intervention](CS1/Cross-Culture/out/YI_Ran_21122200512_11th.pdf) |

## コンパイル方法

ソースファイルは `jarticle` ドキュメントクラスを使用したLaTeXで記述されています。再コンパイルするには、日本語処理に対応したLaTeX環境（TeX Liveや`platex`など）が必要です。

**実行コマンド例:**

```bash
cd CS1/week2
platex week2.tex
dvipdfmx week2.dvi
```