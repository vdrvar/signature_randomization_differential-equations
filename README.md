# Randomization and Differential Equations in the Context of the Signature

Simulations related to a Master's Thesis at TU Munich.

This repository contains simulations related to the technique of the randomized signature map and its accompanying results. The goal is to improve the understanding and application of the signature method in machine learning and data analysis.

## Overview

This work theoretically improves and implements a method for learning rough path trajectories using multidimensional analysis, neural differential equations, and randomization. The main focus is on the randomized signature, a key object in this approach, which combines the expressiveness of path signatures with the efficiency of dimensionality reduction.

## Key Theoretical Concepts

### Reservoir Computing and Signatures
The thesis leverages reservoir computing by utilizing the signature of a path, a high-dimensional feature set that captures deep geometric properties of time-series data. This provides a powerful tool for learning dynamics from data streams.
- **Reference:** Thesis Section 2.2 (Page 3)

### Controlled Differential Equations (CDEs)
Controlled differential equations (CDEs) are employed to model the evolution of the signature over time, enabling continuous-time representations essential for reservoir computing.
- **Reference:** Thesis Section 2.3 (Page 10)

### Randomized Dimensionality Reduction
To address computational challenges, the thesis introduces a randomized dimensionality reduction approach based on the Johnson-Lindenstrauss lemma. This approach preserves the essential properties of high-dimensional signatures while reducing computational complexity.
- **Reference:** Thesis Section 3.1 (Page 18)


## Randomized Signature Equation

The key object, the randomized signature, is defined by the following equation:

![Randomized Signature Equation](https://github.com/vdrvar/rand_and_diff_eq_in_the_context_of_the_sig/assets/48907543/4ba0e164-bd4e-4309-abd5-3cfabc8ecdb9)

This equation represents the core of the method, combining signatures with random projections to enhance computational efficiency.

## Example Visualization

Here's an example of how this object looks for a theoretically defined stochastic process:

![Example Visualization](https://github.com/vdrvar/signature-randomization-differential-equations/assets/48907543/169a3272-255e-4b8e-83ab-fb7ea25ee1da)

## Real-World Application

This high-dimensional object, when applied to real-world data, demonstrates the practical utility of the method:

![Real-World Application](https://github.com/vdrvar/rand_and_diff_eq_in_the_context_of_the_sig/assets/48907543/5e6f2927-4bdc-432c-97b2-883ca4858b16)

By fitting a simple linear regression on the randomized signature, it is possible to achieve a decent reconstruction of a very hectic and nonlinear path:

![Reconstruction Example](https://github.com/vdrvar/rand_and_diff_eq_in_the_context_of_the_sig/assets/48907543/276fd6a8-b9fc-4626-9a21-4084ea0e1d28)

## Conclusion

The techniques developed in this thesis offer an innovative approach to time-series forecasting, combining the theoretical rigor of differential equations with the practical efficiency of randomized methods. For more detailed explanations and the full context of these developments, please refer to the thesis document.
