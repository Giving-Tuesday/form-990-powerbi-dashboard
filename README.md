Example PowerBI Dashboard for examining Form 990 data

# Setup

## Executables

### Windows

1. [download PowerBI](https://www.microsoft.com/en-us/download/details.aspx?id=58494)

### OSX

1. Get a Windows Virtual Machine (recommend: [Parallels](https://www.parallels.com/products/desktop/trial/) (paid). Free: can try [Virtualbox](https://www.virtualbox.org/wiki/Downloads)
2. [Download a virtualbox windows virtual machine](https://developer.microsoft.com/en-us/microsoft-edge/tools/vms/)
3. Open your Windows virtual machine
4. Within your Windows virtual machine, [download PowerBI](https://www.microsoft.com/en-us/download/details.aspx?id=58494)

## Data

If you wish to re-run data cleaning procedure (unnecessary):

To download into repository root:

* `Sample_Program_Service_Data.csv` - [Download from Amazon](https://s3.us-east-2.amazonaws.com/datadive-gates92y-seattle/Project+3+-+Form+990+Data/2+-+Clean+Data/Sample_Program_Service_Data.csv) Sample pre-aggregated financial and text data from Form 990s.

In repository:

* clean.tsv
* clean_clustered_forBI.tsv
* clean_res.tsv
* clean_clustered_forBI.csv
* clean_meta.txt


## Code

If you wish to re-run data cleaning procedure (unnecessary):

1. `pip install -r requirements.txt`
2. `jupyter notebook`
3. Open and run `DataCleaningAndClustering.ipynb`

Note: actual clustering code is not provided, and so cannot be re-run.
