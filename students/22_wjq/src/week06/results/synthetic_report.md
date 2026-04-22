# Synthetic Data Benchmark Report

| Model | Fit Time (sec) | R² (Test) |
|-------|----------------|----------|
| CustomOLS | 0.00078 sec | 0.9052 |
| sklearn.LinearRegression | 0.00218 sec | 0.9052 |

## Coefficient Comparison

- True beta: [ 2.  -1.5  3. ]
- CustomOLS beta: [ 2.0068 -1.48    3.0051]
- sklearn beta: [ 2.0068 -1.48    3.0051]
