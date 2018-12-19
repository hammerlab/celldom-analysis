# Celldom Experiment Analysis

For each new imaging experiment, this repo should contain:

- A folder in ```experiments``` named by the experiment (e.g. ```20180217-G1-K562-control-01```)
- A ```README.md``` file at ```experiments/$name/README.md``` with an overview of the experiment
- An ```experiments/$name/config``` folder containing any related configuration files (typically just ```experiment.yaml```)
- An ```experiments/$name/notebook``` folder containing notebooks with commands used to process the experiment or any related analysis
- An ```experiments/$name/data``` folder containing any accompanying data or analysis output files (e.g. manual counting results for comparison to automated results or csv exports of apartment growth rates)
- An ```experiments/$name/media``` folder containing an figures, videos, flowcharts, or other visualization files  

Any other shared resources like chip or cytometer configurations should remain in the core [Celldom](https://github.com/hammerlab/celldom) repository.

