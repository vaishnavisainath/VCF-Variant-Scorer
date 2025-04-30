# VCF Variant Scorer 🧬

This mini project done as part of my Master's program from Univeristy at Buffalo reads a Variant Call Format (VCF) file, parses it into a structured Python dictionary, and scores each genetic variant based on its predicted impact using fields like `SIFT`, `PolyPhen`, and `MutationTaster`.

## What It Does
- Parses VCF files into nested dictionaries by chromosome, position, reference, and alternate alleles.
- Extracts and organizes `INFO` fields from annotated VCFs.
- Applies a custom scoring system to evaluate potential variant impact using prediction fields.

## How It Works
1. `parse_vcf_to_dict()` reads a VCF file and structures the data.
2. `score_prediction_fields()` analyzes prediction-related fields and assigns impact scores.
3. You can use the output to filter or rank variants based on their severity.

## Files
- `py_mini.py` – Main Python script with all functions.
- `mini_project1_data.vcf` – Sample VCF input.
- `mini_project1_data.json` – JSON output of parsed and scored variants
