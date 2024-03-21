## Installation

The main dependencies for this project are MPB and Meep. 

If on Windows, use WSL with Ubuntu. Within your Ubuntu shell, do the following:

```
sudo apt-get install mpb h5utils

# Get conda (substitute your desired prefix)
wget https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh -O miniconda.sh
bash miniconda.sh -b -p <desired_prefix>
export PATH=<desired_prefix>/bin:$PATH


conda create -n mp -c conda-forge pymeep pymeep-extras
conda init
<restart shell or source your .bashrc file>

conda activate mp
```

And be sure to use the `mp` environment for your Jupyter notebook. 

See also:
- https://meep.readthedocs.io/en/latest/Installation/
- https://mpb.readthedocs.io/en/latest/Download/


