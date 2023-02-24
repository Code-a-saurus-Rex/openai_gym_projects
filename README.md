## Requirements

- Xming (Windows - optional)   
- Conda (e.g. miniconda3)  

eval "$(/home/{user}/miniconda3/bin/conda shell.bash hook)"

- WSL2 (Windows - optional)  

## Setup

In your desired terminal install the conda environment  

```
conda install .
```

Activate the conda environment `gym` and test that your environment works (some linux packages may be missing).

## Startup

I am still deciding how to launch my openai gym projects.

Not using docker; we avoid needing nvidia docker  
Using conda; can switch between windows and ubuntu builds more easily
Running Xming, can run in ubuntu/WSL if we need an output device

### Launch (windows)

- Startup Xming by running config.xlaunch to support an output device  

- From your desired terminal export your output device to id 0  for Xming  

- Activate your project conda environment  

```
conda activate gym
```

- Write/run your agents using python   

