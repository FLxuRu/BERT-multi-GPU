# BERT MULTI GPU

BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding

# REQUIREMENT

python 3

tensorflow 1.12.0

# TRAINING

0, edit the input and output file name in `create_pretraining_data.py` and `run_pretraining_gpu_v2.py`

1, run `create_pretraining_data.py`

2, run `run_pretraining_gpu_v2.py`

# PARAMETERS

Edit `n_gpus` in `run_pretraining_gpu_v2.py`

# DATA

In `sample_text.txt`, sentence is end by \n, paragraph is splitted by empty line.

# EXPERIMENT RESULT

Quora question pairs English dataset,

Official BERT: ACC 91.2, AUC 96.9

This BERT with loss 2.05: ACC 89.9, AUC 96.3

# WHY MUST TRAIN FROM SCRATCH

For inference speed research.
