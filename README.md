[![Documentation Status](https://readthedocs.org/projects/cardioemulator/badge/?version=latest)](https://cardioemulator.readthedocs.io/en/latest/?badge=latest)

# cardioemulator

`cardioemulator` is a Python library that allows to construct zero-dimensional emulators of the cardiac electromechanical function.
These emulators, surrogating the pressure-volume relationship of the cardiac chambers, are build through a data-driven automated algorithm on the basis of pressure-volume recordings.
Once constructed, these emulators allow to simulate the cardiac function at a very low computational cost.

For information about the installation and usage of the library, check out the [documentation](http://cardioemulator.rtfd.io/).

## References

F. Regazzoni, A. Quarteroni "[Accelerating the convergence to a limit cycle in 3D cardiac electromechanical simulations through a data-driven 0D emulator](https://www.mate.polimi.it/biblioteca/add/qmox/35-2021.pdf)", *Computers in Biology and Medicine* (2021)

## Citing

Please cite this library as:

```bibtex
@article{regazzoni2021cardioemulator,
    author  = {Regazzoni, F. and Quarteroni, A.},
    title   = {Accelerating the convergence to a limit cycle in 3D cardiac
               electromechanical simulations through a data-driven 0D emulator},
    journal = {Computers in Biology and Medicine},
    year    = {2021}
}
```

## Contacts

Francesco Regazzoni, MOX - Politecnico di Milano (<francesco.regazzoni@polimi.it>)