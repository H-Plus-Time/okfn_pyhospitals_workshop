# Prerequisites
* A working python 3 installation, including pip.
* all packages contained in requirements.txt (or env.yml).

# Quick setup
If you're running a conda installation, simply run:
```bash
conda env create -f env.yml -n okfn_pyhospitals
source activate okfn_pyhospitals
```

Note, if running Windows, the source keyword isn't needed.

Or, without conda:
```bash
cd <working_dir>
virtualenv create -p /path/to/python3 okfn_pyhospitals
source activate okfn_pyhospitals
pip install -r requirements.txt
```

# Clean up
```bash
conda env remove -n okfn_pyhospitals
```

If using pip, just delete the env:
```bash
cd <working_dir>
rm -rf okfn_pyhospitals
```
