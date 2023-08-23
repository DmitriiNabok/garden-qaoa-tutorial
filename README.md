# Garden Optimization Problem solved with QAOA

The tutorial guides into the QUBO formulation of the Garden Optimization Problem and its solution using the Quantum Approximate Optimization Algorithm (QAOA) employing the Qiskit quantum development toolkit.

#### Setup a new local python environment and switch to it

```bash
python3 -m venv myenv
source myenv/bin/activate
```

#### Install packages

```bash
pip install qiskit 'qiskit-optimization[cplex]' matplotlib pandas networkx openpyxl jupyterlab ipywidgets
```

#### Add the new tutorial environment to the list of the Jupyter kernels

```bash
python -m ipykernel install --name=myenv --user
```

### Run JupyterLab

```bash
jupyter lab
```
