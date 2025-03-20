# FUSION-TWAS-pipeline

Follow the steps in FUSION github to download files

http://gusevlab.org/projects/fusion/

## Installation

FUSION is only compatible with R 3.6 and requires a number of packages that are not available for newer versions of R.
For this reason we have gathered all these packages in an environment called FUSION. To download and activate the environment:

```bash
git clone https://github.com/fischkas/FUSION-TWAS-pipeline.git
cd FUSION
conda env create --file FUSION.yml
source activate FUSION
