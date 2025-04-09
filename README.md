# Yambopy examples

## Installation on Stokes cluster

> pip install yambopy

## Example

> module load python

Modify *exc_kspace_plot.py* script:

```
    states = [1,1]
```

and change the output

```
        plt.savefig("figure_1.pdf")
        plt.show()
```

Run the script

> python exc_kspace_plot.py

