# SciTab
The project page for "SCITAB: A Challenging Benchmark for Compositional Reasoning and Claim Verification on Scientific Tables

## Introduction

This repository contains the code and data for the paper [SCITAB: A Challenging Benchmark for Compositional Reasoning and Claim Verification on Scientific Tables](). 

![alt text](https://github.com/czyssrs/FinQA/blob/main/eg-intro.png?raw=true)
## Dataset

The dataset is stored as json files in folder "dataset", each entry has the following format:

```bash
"paper": the paper name;
"paper_id": the paper id;
"table_cpation": the table caption;
"table_column_names": the table column names;
"table_content_values": the table content;
"id": the unique claim id;
"claim": the claim texts;
"label": the label of the claim, one of the labels from {supports, refutes, not enough info};
"table_id": the unique table id.   
```

## Citation

If you find this project useful, please cite it using the following format: 

```bash

```