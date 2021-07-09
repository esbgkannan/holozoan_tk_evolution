# Evolution of the Holozoan Tyrosine Kinome
 
This repository serves as an archive for the code which was used for the analyses described "Evolution of the Holozoan Tyrosine Kinome". The original analyses were performed within computational notebooks using the JupyterLab framework. The contents of these notebooks can typically be viewed on the GitHub website without the need to download the entire repository. If the notebook fails to load in your browser, try reloading.

## Operating System

Ubuntu 18.04.4

## Getting started
Use these commands to download the repository and necesary datasets.
```
# download this repository
git clone https://github.com/esbgkannan/holozoan_tk_evolution
cd holozoan_tk_evolution

# decompress the files
unzip data.zip
unzip HelperBunny.zip
```

## Python modules
Install the necessary Python 3 modules which are required to run the code. The specific versions of each module which were used in the orginal code are provided in the "requirements.txt" file.
```
python3 -m pip install matplotlib seaborn PyYAML numpy pandas networkx scipy requests Pillow bokeh panel
```
