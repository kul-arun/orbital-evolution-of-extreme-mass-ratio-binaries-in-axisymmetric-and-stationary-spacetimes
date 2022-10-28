
# Orbital Evolution of Extreme Mass Ratio Binaries

A simple program that calculates and plots the orbital evolution of extreme mass ratio binaries in stationary and axisymmetric spacetimes, according to Einstein's general theory of relativty.

## Theoretical Knowledge

The relevant physics and assumptions that went into the calculation of the orbits are included in `theory.pdf`.

## Installation

* **Python**

Install Python 3.7 or higher. Create a virtual environment with:

```
python3 -m venv <virtual-environment-name>
```

Example: To create a virtual environment called `orbital-evolution`, use

```
python3 -m venv orbital-evolution
```

Activate the virtual environment with:
```
source <virtual-environment-name>/bin/activate
``` 

The virtual environment can be deactivated with:
```
deactivate
```

* **Jupyter Notebook** 

Install Jupyter Notebook with:
```
pip install notebook
```
To run the notebook:
```
jupyter notebook
```
* **Additional Requirements**

Install the necessary packages listed in `requirements.txt` with:
```
pip install -r requirements.txt
```
## Output 

The 3D plot of the orbital evolution is saved in the `output` directory as an `HTML` file 

## Examples

Orbital evolution in the the following spacetimes are provided in the `example` directory:

* Schwarzschild spacetime
* Kerr spacetime