# ellie-keys
Ellie's KEYS project

install copilot
conda install mamba -n base -c conda-forge
mamba env create -f enviornment.yml
conda activate heatmap
jupyter lab

conda deactivate && conda activate heatmap && ipython kernel install --name "heatmap" --user
