#### Installing the required software with conda
```shell
# create a new conda environment called bioinformatics with biopython=1.70
conda create -n bioinformatics biopython biopython=1.70

# activate the environment
conda activate bioinformatics

# install the core packages
conda install scipy matplotlib pip pandas cython numba scikit-learn seaborn pysam pyvcf simuPOP dendropy rpy2

# get the metadata file from the 1,000 Genomes sequence index
wget -c ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/historical_data/former_toplevel/sequence.index

# download jupyter notebook on windows
pip install jupyter -i http://pypi.douban.com/simple --trusted-host pypi.douban.com

# Run jupyter notebook on windows
jupyter notebook
```
- **rpy2** provides a declarative interface from Python to R.
