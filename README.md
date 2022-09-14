
# Learning a Neural Pareto Manifold Extractor with Constraints

A scalable Pareto manifold approximation scheme for high-dimensional models, using Fritz-John Conditions for Constrained Multi-Objective Optimization problems. 


## Structure

- Folder 'hnpf' contains the basic Fritz John Conditions
- Fodler 'suhnpf' contains the scalable solver for benchmarking
- Folder 'multimnist' contains the code for finding weights on Multi-MNIST

## Requirements

This codebase requires is designed around Python 3.7 and Tensorflow 2.8
## Citation

### Authors

*Soumyajit Gupta ([@smjtgupta](https://github.com/smjtgupta)), Gurpreet Singh, Raghu Bollapragada, Matthew Lease*

### Abstract

Multi-objective optimization (MOO) problems require balancing competing objectives, often under
constraints. The *Pareto optimal* solution set defines all possible optimal trade-offs over such objectives.
In this work, we present a novel method for *Pareto-front learning*: inducing the full Pareto manifold
at train-time so users can pick any desired optimal trade-off point at run-time. Our key insight is to
exploit Fritz-John Conditions for a novel guided *double gradient descent* strategy. Evaluation on
synthetic benchmark problems allows us to vary MOO problem difficulty in controlled fashion and
measure accuracy *vs.* known analytic solutions. We further test scalability and generalization in learn-
ing optimal neural model parameterizations for Multi-Task Learning (MTL) on image classification. Results show consistent improvement in accuracy and efficiency over prior MTL methods as
well as techniques from operations research.

[[Arxiv Paper]](https://arxiv.org/pdf/2110.15442.pdf)

To cite this work, please follow the given format.

```bibtex
@inproceedings{gupta2022learning,
  title={Learning a Neural Pareto Manifold Extractor with Constraints},
  author={Gupta, Soumyajit and Singh, Gurpreet and Bollapragada, Raghu and Lease, Matthew},
  booktitle={The 38th Conference on Uncertainty in Artificial Intelligence},
  year={2022}
}
```