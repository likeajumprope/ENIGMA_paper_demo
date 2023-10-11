# ENIGMA paper demo
This is a repository to demo different site effect correction methdos. This repository will be demoed at the ENIGMA methdos meeting in Antalya, 2023.

## How to work with this repository:

We suggest to run this notebook within an environment. The following commands require previous installation of anaconda3.

### Create an environment:

```
conda create --name ENIGMA_site_effects
```
### Activate your environment:

```
source activate ENIGMA_site_effects
```
### Install relevant packages
```
conda install pip pandas scipy
````
#### Install pcntoolkit for nomrative modelling (plus dependencies)
```
pip install pcntoolkit
```
#### Install ComBat, ComBat GAM and CovBat

##### Standard Combat
```
pip install neuroComBat
```
##### ComBat GAM
