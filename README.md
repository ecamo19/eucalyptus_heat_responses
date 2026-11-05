# [![DOI]()

# License
- Code: [MIT](LICENSE)
- Data in `01_euc_saligna/`, `02_euc_grandis/`, `03_euc_crebra/` `04_euc_dunnii`, `05_euc_tereticornis`, `06_euc_melliodora`, `07_euc_sideroxylum`, `07_euc_sideroxylum`,: [CC BY 4.0](LICENSES/CC-BY-4.0.txt) — please cite as below:


# Code Reproducibility

## Platforms supported
+ Linux:
+ Windonws e62a:
+ MacOS:
+ MacOS-Arm

This repository contains all the raw data and code used in the paper titled:

"Lack of coordination between drought traits and heat responses in Fast-Risky and Slow-Safe tree species".

You can report any issue with the repository to erickcamo19@gmail.com

Or visit the github repository at https://github.com/ecamo19/eucalyptus_heat_responses/

For reproducing the results in the repository:

1) Install [pixi](https://pixi.prefix.dev/latest/#installation) for getting the necessary R dependecies
2) Download this github repository: 

`git clone https://github.com/ecamo19/eucalyptus_heat_responses/`

3) Once you have setup your the working directory to the downloaded repository, 
enter the following terminal command:

`pixi shell` 

4) Open a jupyter server using the following terminal command:

`pixi run jupyter_nb`

This might take several minutes while the dependencies are installed

5) Finally, to execute the code in each `.ipynb` file make sure the notebook is 
Trusted (if a Not Trusted flag shows up inside the notebook, change it to 
Trusted by clicking over it. This is located at the top right) and the 
kernel R (Pixi) is selected.

![](./r_pixi.png)
