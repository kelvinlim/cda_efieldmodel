# cda_efieldmodel


## Setup for running

```
export PATH=~/Projects/cda_tools2:$PATH
source ~/Venv/cda_tools2/bin/activate
```

For MSI 
```
module load java/openjdk-17.0.2
module load graphviz

```
## To run causal modeling

```
run_parse2.py --mdir proj_efield
run_causal2.py --mdir proj_efield

```
