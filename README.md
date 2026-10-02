# EDS 220 Student Notebooks

Pre-filled Jupyter notebooks for students to work through during class sessions of [EDS 220: Working with Environmental Datasets](https://meds-eds-220.github.io/MEDS-eds-220-course/), a course in the [Master of Environmental Data Science (MEDS)](https://bren.ucsb.edu/masters-programs/master-environmental-data-science) program at UC Santa Barbara's Bren School.

Each notebook follows a lesson or discussion section from the course. They contain the lesson's narrative, learning objectives, and data descriptions, with code cells left for students to complete in class. Full lesson materials and solutions are on the [course website](https://meds-eds-220.github.io/MEDS-eds-220-course/).

Topics covered include:

- Python review and `pandas` subsetting
- Writing functions and refactoring code
- Vector data with `geopandas`: reprojecting, merging, and clipping
- Multidimensional data with NetCDF and `xarray`
- Raster data with `rioxarray`
- Accessing satellite imagery through STAC catalogs
- Land cover statistics, linear regression, and making GIFs



## Data access

No data is stored in this repository. Depending on the notebook, data is accessed in one of three ways:

- **Read directly from a URL** (e.g., CSV files hosted on GitHub or the [DataONE](https://www.dataone.org/) repository). No download needed.
- **Queried from the [Microsoft Planetary Computer](https://planetarycomputer.microsoft.com/) STAC catalog** using `pystac_client`. No download needed.
- **Read from a local `data/` folder** next to the notebooks. Files are not tracked by git (see `.gitignore`); download them by following the "About the data" section at the top of each notebook or the corresponding lesson on the [course website](https://meds-eds-220.github.io/MEDS-eds-220-course/).

Each notebook's "About the data" section gives the full citation and source link for every dataset it uses.

## Authors

- [Carmen Galaz García](https://github.com/carmengg), course instructor

## References and acknowledgments

- Lesson content is adapted from the [EDS 220 course website](https://meds-eds-220.github.io/MEDS-eds-220-course/) ([source repository](https://github.com/MEDS-eds-220/MEDS-eds-220-course)).
- Dataset citations are listed in each notebook and on the corresponding course web page.
- README written following the [MEDS README guidelines](https://ucsb-meds.github.io/README-guidelines/).
