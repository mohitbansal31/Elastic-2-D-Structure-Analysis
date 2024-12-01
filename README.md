# Elastic Structural Analysis of 2-D Structures Using the Direct Stiffness Method

This repository contains a Python implementation of the **Direct Stiffness Method (DSM)** for performing elastic structural analysis of 2D structures. The method is commonly used for analyzing statically indeterminate frames and other complex structures.

## Project Objective

Develop a generic Python code to:
- Take geometry and loading details as input.
- Perform structural analysis using the **Direct Stiffness Method**.

The implementation has been validated against results from **STAAD Pro**, with a marginal error of ~2%, demonstrating its effectiveness.

---

## Features

- Computes **global stiffness matrix** and **fixed-end force vectors** for structural elements.
- Solves for **displacement vectors** and **reaction forces**.
- Calculates **member-end forces** and **moments**.
- Incorporates support settlement considerations for real-world applications.

---

## Methodology

1. **Input Data**:
   - Structural geometry, material properties, and loading details.

2. **Transformation Matrices**:
   - Converts local coordinate matrices to global coordinate matrices.

3. **Stiffness Matrix Assembly**:
   - Builds the global stiffness matrix from individual member matrices.

4. **Force and Displacement Analysis**:
   - Solves for active displacement vectors using matrix operations.
   - Computes reaction forces and moments for supports.

5. **Validation**:
   - Results validated against **STAAD Pro** for multiple structural models.

---
<!-- 
## Sample Output

### Structure 1
- **Displacements**:
  - Python code: `Δ = [values]`
  - STAAD Pro: `Δ = [values]`
- **Moments**: ...
- **Reactions**: ...

(Include graphs or tables here)

--- -->

## Repository Contents

- **`Direct_Stiffness_Method.ipynb`**: Python implementation in Jupyter Notebook.
- **`Report.pdf`**: Detailed project report, including methodology, results, and validation.
- **Sample Input Files**:
  - Node data
  - Member data

---

## Requirements

- Python 3.x
- Libraries:
  - NumPy
  - Matplotlib (for optional visualization)

---

## Validation Results

The Python code results are compared against **STAAD Pro**, demonstrating a marginal error of ~2%, attributed to:
- Numerical approximations
- Element discretization
- Computational precision

---

## Conclusion

The Python implementation of the **Direct Stiffness Method** provides a reliable and accurate tool for structural analysis, with minimal error compared to industry-standard software. The incorporation of support settlement and other practical considerations makes it a versatile tool for academic and professional applications.

---

## Contributors

- Bhanu Pratap  
- Mohit Bansal  
- Rohan Choudhary  

---

## License

This project is licensed under the [MIT License](LICENSE).
