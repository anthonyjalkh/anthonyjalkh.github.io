# Gravitational Potential & Numerical Orbits

Test post for LaTeX and code rendering:

$$\nabla^2 \Phi = 4 \pi G \rho$$

```python
import numpy as np

def gravitational_force(m1, m2, r):
    G = 6.67430e-11
    return G * (m1 * m2) / (r**2)
```
