The main code is Lab2.ipynb file. You can find every step and results of these snippets by running them in Jupyter Notebook.

beh2_opt.inp and h2s_opt.inp files are input files for Orca app. Orca performs DFT on these file then gives outputs. For this simulation, the most important file is .xyz file,
because it gives us cartesian coordinates of atoms. To perfom DTF on Linux terminal
```bash
orca beh2_opt.inp > beh2_opt.out
orca beh2_opt.inp > beh2_opt.out
```

Now files are suitable for main code Lab2.ipynb

This file requires a few Python modules. To install these modeules:

```bash
pip install py3DMol
pip install IPython
pip install rdkit
```
