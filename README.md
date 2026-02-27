# MD-Lennard-Jones-from-scratch

## Setting Up Your Local Python Environment (Windows)

Follow these steps to set up a local Python environment and install the required packages:

1. **Install Python**
   - Download and install Python (version 3.8 or higher recommended) from [python.org](https://www.python.org/downloads/).
   - During installation, make sure to check the box **"Add Python to PATH"**.

2. **Open Command Prompt**
   - Press `Win + R`, type `cmd`, and press Enter.

3. **Navigate to the Project Directory**
   - Use the `cd` command to change to the project folder. For example:
     ```sh
     cd "D:\Users\eajfpeters\OneDrive - TU Eindhoven\Documents\Teaching\Molecular Simulations\MD and MC\MD-Lennard-Jones-from-scratch"
     ```

4. **(Optional) Create a Virtual Environment**
   - It is recommended to use a virtual environment to avoid conflicts:
     ```sh
     python -m venv .venv
     .venv\Scripts\activate
     ```

5. **Install Required Packages**
   - Use pip to install all dependencies from `requirements.txt`:
     ```sh
     pip install -r requirements.txt
     ```

---

## About the Notebook

The notebook `MD_LJ_Simulation.ipynb` is part of a lectorial on Molecular Dynamics. It provides a step-by-step implementation of a Molecular Dynamics simulation using the Lennard-Jones potential, designed for educational purposes. The notebook guides you through the fundamental concepts and practical coding aspects of simulating molecular systems from scratch.

Explore the notebook to learn about:
- Setting up a molecular system
- Implementing the Lennard-Jones potential
- Integrating equations of motion
- Analyzing simulation results

This resource is ideal for students and educators in computational chemical engineering and molecular simulations.