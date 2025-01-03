# Apple_Silicon_LCM_experiments
MLX implementation of Richard Aragon's experiments with the Meta Large Context Model Architecture.

Optimized for M1 Ultra Studio 128Gb unified 48GPU. (Loss of ~.16 in 40 epochs.)

A lot of credit goes to Anthropic's Claude Sonnet 3.5 for working this out. Well worth paying for Pro.

Set up a conda environment with python 3.11.11 (Jupyter was failing on 3.13+) and download the glove dataset folder to the same directory where you save the notebook.
