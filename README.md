# msbuddy - Python packge & Command-line tool
![Maintainer](https://img.shields.io/badge/maintainer-Shipei_Xing-blue)
[![PyPI](https://img.shields.io/pypi/v/msbuddy?color=green)](https://pypi.org/project/msbuddy/)
[![docs](https://readthedocs.org/projects/msbuddy/badge/?version=latest)](https://msbuddy.readthedocs.io/en/latest/?badge=latest)
[![Generic badge](https://img.shields.io/badge/msbuddy-mass_spec_tools-<COLOR>.svg)](https://github.com/Philipbear/msbuddy)

<p align="center">
  <img src="https://github.com/Philipbear/msbuddy/blob/main/logo/logo.svg" alt="Sample Image" height="100"/>
</p>


We have now released `msbuddy` as a Python package and a command-line tool.

**msbuddy**: https://github.com/Philipbear/msbuddy

**msbuddy documentation**: https://msbuddy.readthedocs.io/en/latest


&nbsp;
&nbsp;

> **Note**: `msbuddy` and `BUDDY` and two different tools that share the same core algorithm. They generate different annotation results.
`msbuddy` is newly developed for flexible molecular formula analysis with refined algorithmic design and model training.
We'd recommend using `msbuddy` for your latest analysis.


&nbsp;
&nbsp;

# BUDDY - GUI
[![Generic badge](https://img.shields.io/badge/BUDDY-ver_1.7-<COLOR>.svg)](https://github.com/Philipbear/BUDDY_Metabolomics)
![Maintainer](https://img.shields.io/badge/maintainer-Shipei_Xing-blue)

<img src = "https://github.com/Philipbear/BUDDY_Metabolomics/blob/main/image/AppIcon.png" align="right" width = "150" height = "150">

`BUDDY` is an open-source cheminformatic software platform developed for MS-based metabolomics research, capitalizing on **bottom-up MS/MS interrogation** and **experiment-specific global peak annotation**.

Bottom-up MS/MS interrogation aims to determine molecular formulae for all metabolic features with significance estimation. Experiment-specific global peak annotation is achieved to select the optimal molecular network considering both individual peak annotations and peak interrelationships.

Check out [our Youtube tutorial video](https://www.youtube.com/watch?v=Ne_Y0vZ0WKI) here.


&nbsp;
&nbsp;


## Quick Start
### Installation
`BUDDY` can be freely downloaded on this [GitHub release page](https://github.com/Philipbear/BUDDY_Metabolomics/releases).

We provide a graphical user interface shown as below.
<img src = "https://github.com/Philipbear/BUDDY_Metabolomics/blob/main/image/GUI.png" width = "850" >


### Task
- MS/MS library search
- Bottom-up MS/MS interrogation
- Experiment-specific global peak annotation
### File import 
- Single query import (pop-up window) 
- Batch import (metabolic feature table, mzML file, mgf file)
### Result export
- Single export (a single query feature) 
- Batch export in a hierarchical manner (file – metabolic feature – candidate formula – explained MS/MS)

## User Manual
Detailed instructions on `BUDDY` can be found in [BUDDY user manual](https://philipbear.github.io/BUDDY_Metabolomics).
## Citation
> S. Xing et al. BUDDY: molecular formula discovery via bottom-up MS/MS interrogation. **Nature Methods** 2023. [DOI: 10.1038/s41592-023-01850-x](https://doi.org/10.1038/s41592-023-01850-x)


