# kal-cal
## Kalman Filter and Smoother RI Calibration

**kal-cal** is a Python library developed to provide proof-of-concept tools for *Kalman Filtering and Smoothing Theory* (see [Bayesian Filtering and Smoothing by Simo S ̈arkk ̈a](https://users.aalto.fi/~ssarkka/pub/cup_book_online_20131111.pdf)) as a replacement calibration framework for *Radio-Interoferometric Gains Calibration* (see [Non-linear Kalman Filters for calibration in radio interferometry by Cyril Tasse](https://arxiv.org/abs/1403.6308)). This library is part of the master's thesis work of *Brian Welman* (@[brianWelman2](https://github.com/brianwelman2) on github) through [Radio Astronomy Techniques and Technologies](http://www.ratt-ru.org/) under [SARAO](https://www.sarao.ac.za/) during the period of 2020 to 2021.

## Requirements
The only external requirement is the `casa` command from [`casalite`](https://casa.nrao.edu/casa_obtaining.shtml). Otherwise, all Python packages are listed in [`requirements.txt`](https://github.com/brianwelman2/kal-cal/blob/main/requirements.txt).

## Installation

Firstly, you need at least `python3`, or even better `python3.6.9`, as this is the version the library was developed on. Use the package manager [`pip`](https://pip.pypa.io/en/stable/) to install **kal-cal** as follows:

```bash
pip install https://github.com/brianwelman2/kal-cal/archive/refs/heads/main.zip
```

## Usage
To import **kal-cal**:
```python
import kalcal
```
## Documentation
*TBD*

## CI
This library uses [github-actions](https://github.com/features/actions) for continuous integration tests on the same repository.

## License
This package uses the [MIT](https://choosealicense.com/licenses/mit/) license.