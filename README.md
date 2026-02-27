# MD-Lennard-Jones-from-scratch

## About the Notebook

The notebook `MD_LJ_Simulation.ipynb` is part of a lectorial on Molecular Dynamics. It provides a step-by-step implementation of a Molecular Dynamics simulation using the Lennard–Jones potential, designed for educational purposes.

The notebook guides you through the fundamental concepts and practical coding aspects of simulating molecular systems from scratch.

You will learn about:

* Setting up a molecular system
* Implementing the Lennard–Jones potential
* Integrating the equations of motion (Velocity–Verlet)
* Analyzing simulation results

This repository will be updated live during class. Please follow the workflow below to stay synchronized.

---

## Workflow: Getting Started in Class

To keep track of your own progress and allow quick feedback, please use the following workflow.

### 1. Fork the Repository

1. Log in to GitHub.
2. Open this repository in your browser.
3. Click **Fork** (top right).

This creates your own copy under your GitHub account.



### 2. Clone Your Fork in VS Code

1. Open VS Code.
2. Press **Ctrl + Shift + P**
3. Type: `Git: Clone`
4. Paste the URL of **your fork** (not the original repository).
5. Choose a **clean, empty folder** on your computer.
6. Open the repository when prompted.

You now work in your own copy.



### 3. During Class: Stay Synchronized

When a new checkpoint is announced:

1. Go to **your fork on GitHub** in the browser.
2. Click **Sync fork** → **Update branch**.
3. Open VS Code.
4. Go to the **Source Control** panel.
5. Click the three dots (…) → **Pull**.

Your fork is now updated with the latest in-class changes.

Continue implementing in your own copy.



### 4. Commit Your Work Regularly

Commit small, logical steps.

In VS Code:

1. Open **Source Control**.
2. Write a short message (e.g. `Implemented Velocity–Verlet integrator`).
3. Click **Commit**.
4. Click **Sync Changes**.

Frequent commits make debugging and feedback much easier.



### 5. Optional: Share Your Progress for Feedback

If you would like feedback:

1. Go to your fork on GitHub.
2. Click **Pull Requests**.
3. Click **New Pull Request**.
4. Select your working branch.
5. Choose **Create Draft Pull Request**.

Add a short note describing:

* What works
* What does not work yet
* Where you are unsure

Pull requests are used only for feedback and progress monitoring.
They will not be graded.

---

## Setting Up Your Local Python Environment

If you do not yet have a Python environment set up, follow the instructions below **inside the folder where you cloned your fork**.



### Windows

1. Install Python (version 3.8 or higher recommended) from
   [https://www.python.org/downloads/](https://www.python.org/downloads/)
   During installation, check **"Add Python to PATH"**.

2. Open Command Prompt.

3. Navigate to your repository folder:

```
cd "C:\path\to\your\MD-Lennard-Jones-from-scratch"
```

4. Create and activate a virtual environment:

```
python -m venv .venv
.venv\Scripts\activate
```

5. Install required packages:

```
pip install -r requirements.txt
```



### macOS / Linux

1. Open Terminal.
2. Navigate to your repository folder:

```
cd /path/to/your/MD-Lennard-Jones-from-scratch
```

3. Create and activate a virtual environment:

```
python3 -m venv .venv
source .venv/bin/activate
```

4. Install required packages:

```
pip install -r requirements.txt
```



VS Code will usually detect the `.venv` environment automatically and suggest selecting it as the Python interpreter.

If not, press:

```
Ctrl + Shift + P → Python: Select Interpreter
```

and choose the `.venv` environment.



This setup only needs to be done once.
