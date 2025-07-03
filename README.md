# Monte-Carlo-Estimation-CPU-vs.-GPU-

#**Project Overview**
**Monte Carlo π Estimation (CPU vs. GPU)**

---



**Objective**: Estimate the value of π using the Monte Carlo method on both CPU and GPU, then compare their performance.

**1.Methodology**:

Monte Carlo Principle: Randomly generate points within a unit square. The ratio of points that fall inside the unit circle to the total number of points approximates π/4.

**2.Implementation:**

**CPU Version**: Utilize NumPy to generate random points and perform
calculations.

**GPU Version**: Leverage CuPy, a GPU-accelerated library with a NumPy-like interface, to execute the same operations on the GPU.

**3.Performance Comparison**: Measure and compare the execution times of both implementations to analyze the speedup achieved by GPU acceleration.



---

