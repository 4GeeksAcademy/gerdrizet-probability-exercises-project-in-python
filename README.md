# Probability Exercises with Python Simulations

[![Codespaces Prebuilds](https://github.com/4GeeksAcademy/gperdrizet-probability-exercises-project-in-python/actions/workflows/codespaces/create_codespaces_prebuilds/badge.svg)](https://github.com/4GeeksAcademy/gperdrizet-probability-exercises-project-in-python/actions/workflows/codespaces/create_codespaces_prebuilds)

A hands-on probability project that teaches statistical concepts through Monte Carlo simulations and empirical probability calculations using Python. This project demonstrates how to use computational methods to verify theoretical probability outcomes through practical experiments.

![Project Preview](assets/preview.jpeg)


## Project Overview

This project explores fundamental probability concepts through **Monte Carlo simulations** - a computational method that uses repeated random sampling to solve problems that might be deterministic in principle. Students will learn to:

- Simulate random experiments using Python
- Calculate empirical probabilities through repeated trials
- Compare simulation results with theoretical probability
- Apply the Law of Large Numbers in practice
- Work with discrete probability distributions


## Getting Started

### Option 1: GitHub Codespaces (Recommended)

1. **Fork the Repository**
   - Click the "Fork" button on the top right of the GitHub repository page
   - 4Geeks students: set 4GeeksAcademy as the owner - 4Geeks pays for your codespace usage. All others, set yourself as the owner
   - Give the fork a descriptive name. 4Geeks students: I recommend including your GitHub username to help in finding the fork if you lose the link
   - Click "Create fork"
   - 4Geeks students: bookmark or otherwise save the link to your fork

2. **Create a GitHub Codespace**
   - On your forked repository, click the "Code" button
   - Select "Create codespace on main"
   - If the "Create codespace on main" option is grayed out - go to your codespaces list from the three-bar menu at the upper left and delete an old codespace
   - Wait for the environment to load (Python 3.11 is pre-installed)

3. **Start Working**
   - Open `notebooks/assignment.ipynb` in the Jupyter interface
   - Follow the step-by-step instructions in the notebook

### Option 2: Local Development

1. **Prerequisites**
   - Git
   - Python >= 3.11

2. **Fork the repository**
   - Click the "Fork" button on the top right of the GitHub repository page
   - Optional: give the fork a new name and/or description
   - Click "Create fork"

3. **Clone the repository**
   - From your fork of the repository, click the green "Code" button at the upper right
   - From the "Local" tab, select HTTPS and copy the link
   - Run the following commands on your machine, replacing `<LINK>` and `<REPO_NAME>`

   ```bash
   git clone <LINK>
   cd <REPO_NAME>
   ```

4. **Set Up Environment**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

5. **Launch Jupyter & start the notebook**
   ```bash
   jupyter notebook notebooks/assignment.ipynb
   ```


## Project Structure

```
├── .devcontainer/        # Development container configuration
├── assets/               # Images and other files
│
├── notebooks/            # Jupyter notebook directory
│   ├── assignment.ipynb  # Assignment notebook with exercises
│   └── solution.ipynb    # Solution notebook with completed code
│
├── .gitignore            # Files/directories not tracked by git
└── README.md             # Project documentation
```


## Learning Objectives

1. **Statistical Thinking**: Design experiments to test probability hypotheses
2. **Computational Problem Solving**: Translate probability problems into code
3. **Data Analysis**: Interpret simulation results and compare with theory
4. **Python Programming**: Use random modules and control structures effectively
5. **Scientific Method**: Validate theoretical predictions through experimentation


## Technologies Used

- **Python 3.11**: Core programming language
- **Random Module**: For generating random numbers and simulating experiments
- **Jupyter Notebooks**: Interactive development and documentation
- **GitHub Codespaces**: Cloud-based development environment


## Contributing

This is an educational project. Contributions for improving the exercises or adding new probability scenarios are welcome:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

