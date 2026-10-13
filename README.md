# Risk-Based Active Learning for Hazard Emulators
A repository exploring the use of risk-based learning functions to train hazard emulators via active learning.

## Repository Contents
* `demo.ipynb`: a demo notebook illustrating different sampling priorities for hazards vs. risk-based learning functions in a toy problem.
* `LICSENSE`
* `README`
* `environment.yml`: file with packages used in the `conda` environment

## Interactive Demo
If you would like to run the contents of `demo.ipynb` in a cloud-based environment, click the Binder badge below:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jbbutler/risk-learning/HEAD?urlpath=%2Fdoc%2Ftree%2Fdemo.ipynb)

## Running it Locally

To run the demo locally, first clone the repository:

```
git clone https://github.com/jbbutler/risk-learning.git
```

Then, create the `conda` environment:

```
conda env create -f environment.yml
```

Finally, register the environment with a Jupyter kernel:

```
python -m ipykernel install --user --name=risk-learning --display-name "risk-learning"
```