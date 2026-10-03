# FASTA Sequence Analyzer 🧬

A beginner-friendly Python project that reads a FASTA file and performs basic DNA sequence analysis.

## 📌 What This Project Does

This program can:

* Read a FASTA file
* Extract the FASTA header
* Join DNA sequences spread across multiple lines
* Calculate DNA sequence length
* Count A, T, G, and C nucleotides
* Calculate GC content

## 🧬 Example FASTA File

```text
>Sample_DNA_Sequence
ATGCAATGTGGACCATGGCATAG
CAAATTGGCAATGCA
AATGCAAAATCCGAGTAAATGCCCCATGCAT
```

The program combines the multiple sequence lines into one continuous DNA sequence before performing the analysis.

## 🔬 Example Output

```text
Header: >Sample_DNA_Sequence
Sequence: ATGCAATGTGGACCATGGCATAGCAAATTGGCAATGCAAATGCAAAATCCGAGTAAATGCCCCATGCAT
Sequence length: 70

A: ...
T: ...
G: ...
C: ...

GC content: ... %
```

## 🛠️ Concepts Used

* Python file handling
* `open()` and `close()`
* `.read()`
* `.splitlines()`
* String joining with `"".join()`
* `.count()`
* `len()`
* Basic mathematical calculations
* FASTA file format

## 🎯 Learning Goal

This project was created to practice Python programming through a real bioinformatics use case.

It is part of my journey of combining **Biotechnology + Python + Bioinformatics**.

## 🚀 Future Improvements

Possible future additions:

* Validate whether the sequence contains only A, T, G, and C
* Calculate AT content
* Calculate nucleotide percentages
* Analyze multiple FASTA sequences
* Use Biopython for FASTA parsing

## 👩‍💻 Author

Akshara Sharma

**Biotechnology Student | Learning Python & Bioinformatics**

