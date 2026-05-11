# Gff2Seq

A lightweight and efficient bioinformatics tool to extract sequences (Protein, CDS, or Genomic DNA) based on GFF/GTF annotations.

## Features
- **Fast Extraction**: Powered by `awk` and `gffread` for high-performance sequence retrieval.
- **Robust Parsing**: Handles GFF3/GTF attributes and automatically manages 1-based to 0-based coordinate conversion.
- **Strand-Aware**: Supports strand-specific extraction for genomic sequences.
- **Easy to Use**: A single bash script with clear options.

## Requirements
- `gffread` (for Protein and CDS extraction)
- `bedtools` (for Genomic sequence extraction)
- Standard Unix tools: `awk`, `sed`

## Installation
```bash
git clone [https://github.com/YourUsername/Gff2Seq.git](https://github.com/YourUsername/Gff2Seq.git)
cd Gff2Seq/bin
chmod +x Gff2Seq
export PATH=$PATH:$(pwd)
