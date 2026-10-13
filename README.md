# ML4SCI: Machine Learning for Science

**EECS 195 / EECS 221 · University of California, Irvine · Fall 2026**
Instructor: [Prof. Aparna Chandramowlishwaran](https://aparnamowli.github.io)

**Course website: https://eecs-ml4sci.github.io**

---

## About

ML4SCI covers machine learning methods for modeling, simulating, and discovering structure in the natural world, with an emphasis on physical systems governed by partial differential equations (PDEs).

The course treats scientific ML as its own discipline. Scientific data has structure: conservation laws, symmetries, multiscale dynamics, irregular geometry, and limited or expensive data. Each topic discusses methods to respect that structure.

The material is built to be useful beyond UCI. Lecture slides and notebooks are posted openly on the course website for students, researchers, and instructors anywhere.

## Who this course is for

- Senior undergraduates (EECS 195) and graduate students (EECS 221) in computer science, engineering, physics, applied mathematics, and related fields
- Researchers in the physical sciences who want an introduction to ML for their domain
- ML researchers who want to work on scientific problems
- Instructors looking for material to adapt for their own courses

## Prerequisites

- Linear algebra, multivariable calculus, and probability
- Programming experience in Python
- An introductory machine learning course

Prior exposure to differential equations or numerical methods is helpful.

## Topics

1. **Foundations:** ML fundamentals; PDEs and numerical methods for scientific data
2. **Representations:** data representations, symmetry, invariance, and equivariance
3. **Spatial and temporal modeling:** CNNs, U-Nets, autoregressive rollouts, recurrent networks, neural ODEs, transformers
4. **Evaluation:** how to evaluate scientific ML models
5. **Operator learning and geometry:** neural operators; graph neural networks on meshes
6. **Physics-informed and hybrid learning:** embedding physical constraints; combining solvers with learned models
7. **Generative and probabilistic models:** generative modeling and uncertainty quantification
8. **Scale and understanding:** scaling laws, mixture-of-experts, scientific foundation models, and mechanistic interpretability

See the [schedule](https://eecs-ml4sci.github.io) for the schedule.

## Using the materials

Self-learners can follow the course on the website in order; each lecture lists its readings.

Instructors are welcome to adapt the material for their own teaching. Please credit the course and link back to the website.

Suggestions, corrections, and reports of broken links are welcome through [GitHub Issues](https://github.com/eecs-ml4sci/eecs-ml4sci.github.io/issues).

## Citation

If you use these materials in teaching or research, please cite:

```bibtex
@misc{ml4sci2026,
  author       = {Chandramowlishwaran, Aparna},
  title        = {{ML4SCI}: Machine Learning for Science},
  howpublished = {Course, University of California, Irvine},
  year         = {2026},
  url          = {https://eecs-ml4sci.github.io}
}
```

## License

See [LICENSE](LICENSE) for terms of use.
