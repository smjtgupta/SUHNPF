
# Learning a Neural Pareto Manifold Extractor with Constraints

A scalable Pareto manifold approximation scheme for high-dimensional models, using Fritz-John Conditions for Constrained Multi-Objective Optimization problems. 

---

## Install

```bash
git clone https://github.com/smjtgupta/SUHNPF.git
cd SUHNPF
pip install -r requirements.txt
```

---

## Experiments

- `demo.ipynb' contains the working logic of the solver
- Folder 'examples' contains the cases and solver files

## Requirements

This codebase requires is designed around Python 3.7 and Tensorflow 2.1
Note that Tensorflow might cause issues with symbolic gradient depending
on version. Update accordingly.


### Paper

[[Arxiv Paper]](https://arxiv.org/pdf/2110.15442.pdf)

## Citation

To cite this work, please follow the given format.

```bibtex
@inproceedings{gupta2022learning,
  title={Learning a Neural Pareto Manifold Extractor with Constraints},
  author={Gupta, Soumyajit and Singh, Gurpreet and Bollapragada, Raghu and Lease, Matthew},
  booktitle={The 38th Conference on Uncertainty in Artificial Intelligence},
  year={2022}
}
```