# 
A publicly available Jupyter Notebook Example for plotting output from
the RRFS NA Ensemble running on AWS.

This Notebook is mostly unsupported. Feel free to open an Issue for major
bug fixes.

# Requirements

- Python 3.6+
- XArray
- Matplotlib
- Basemap
- PyNIO
- NumPy
- MetPy


## Supported environments on NOAA Platforms

On NOAA's Jet and Hera, an conda environment exists that will support
the requirements. To activate that environment:

```
module use /contrib/miniconda3/modulefiles
module load miniconda3
conda activate pygraf
```

On Orion, it's slightly different:

```
module use -a /apps/contrib/miniconda3-noaa-gsl/modulefiles
module load miniconda3
conda activate pygraf
```

# Contact

| Name  | Email |
| ----- | ----- |
| Christina Holt   | christina.holt@NOAA.gov |

