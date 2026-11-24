# Vision Language Model Practive
How many labeled OCT scans does a small open vision-language model need to match a 31B model and a task-specific CNN, and does training on the bigger model's outputs help when labels are scarce?

The task: given one OCT B-scan, produce a structured JSON grading report (diagnosis plus the findings behind it).

## Public data only used for this project
https://zenodo.org/records/10839556 OCTDL (2024) Dataset.
+ OCTDL.zip
+ OCTDT_labels.csv

## Hardware, OS, Software
RTX 2070
Ubuntu 24.04
VIM
VS Code
Python

## Phases
+ Get Data and Baseline
+ Eval and 0-shot 
+ Learning Curves
+ Distillation and Ablation
+ Write Up 
