# STalign_LaMannoLab
A repository with notebooks adapted to Gioele La Manno's Lab for alignment of adult and developing mouse brain slices, genes expression and lipids expression data, depending on the purpose.

This repository is based on the use of STalign, a tool that aligns spatial transcriptomics (ST) tissue sections to each other and to 3D atlases like the Allen Brain Atlas using algorithms that build upon diffeomorphic metric mapping.
In particular, we refer to: [STalign: Alignment of spatial transcriptomics data using diffeomorphic metric mapping](https://www.nature.com/articles/s41467-023-43915-7).
You can find the relative GitHub repository at [STalign](https://github.com/JEFworks-Lab/STalign?tab=readme-ov-file#overview).

## Installation
To start using the notebooks in the different folders you must firstly install STalign with:

`pip install --upgrade "git+https://github.com/JEFworks-Lab/STalign.git`.

## Overview
Find three different folders:
- Alignment_and_annotation: these notebooks are specialized in alignment and automatic annotation of mouse (both adult and developing one) brain slices, using Allen Atlas data;
- Genes_Lipids: this notebook is specialized in alignment of two images with genes and lipids expression, deriving from HybISS and MALDI tecnniques;
- STalign_Lipids: this notebook is specialized in alignment of a lipid expression image with the corresponding Allen one.
