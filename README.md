# Psychopy-Experiment-Interface
This is the interface of an experiment of Cognitive Science lab at International Institute of Information Technology (IIIT) Hyderabad. 


## Steps to run
1. Python Version required - 3.10
2. Create a folder where you will download this repo
3. Into the folder
```bash
cd psychopy_Experiment-Inrerface
```
5. Create a conda environment
```bash
conda create -n "psychopy_env" python=3.10
conda activate psychopy_env
```
3. Install the requirements 
```bash
pip install -r requirements.txt
```


## Optional Modifications
- If you want to run the experiment in full screen - there is a window object 'win' setup, modify the `fullscr=False` to `fullscr=True`. 
- If you want to change the Content - I have clearly labelled each section of the code and the stage it belongs to in the experiment - you can modify the content being displatyed on the page from there.


Best of Luck for the Experiment!
