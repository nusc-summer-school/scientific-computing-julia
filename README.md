Scientific Computing with Julia NUSC Summer School 2025


Welcome to the Scientific Computing with Julia workshop for the NUSC Summer School 2025! This repository contains all the materials needed to discover Julia's power for high-performance scientific computing and numerical simulations.

Workshop Overview
This workshop provides a comprehensive introduction to scientific computing using Julia. Participants will learn how to leverage Julia's speed, expressiveness, and numerical capabilities for solving computational problems in various scientific domains.

Learning Objectives
By the end of this workshop, participants will be able to:

Understand Julia's type system and multiple dispatch paradigm
Implement numerical algorithms with high performance
Utilise Julia's ecosystem for scientific computing
Perform data analysis and visualisation with Julia
Conduct numerical simulations and solve differential equations
Leverage parallel and distributed computing
Interface Julia with other languages (Python, C, etc.)
Prerequisites
Programming experience in at least one language (Python, MATLAB, R, etc.)
Basic understanding of linear algebra and calculus
Familiarity with scientific computing concepts
A laptop with Julia 1.9+ installed
Workshop Schedule


Day 1: Julia Fundamentals for Scientific Computing
09:00 - 10:30: Introduction to Julia and Its Ecosystem
10:45 - 12:15: Types, Multiple Dispatch, and Performance
13:30 - 15:00: Linear Algebra and Array Programming
15:15 - 16:45: Data Analysis and Visualization


Day 2: Numerical Methods and Simulations
09:00 - 10:30: Numerical Integration and Optimization
10:45 - 12:15: Solving Ordinary Differential Equations
13:30 - 15:00: Partial Differential Equations and Finite Differences
15:15 - 16:45: Monte Carlo Methods and Stochastic Simulations


Day 3: Advanced Topics and Applications
09:00 - 10:30: Parallel and Distributed Computing
10:45 - 12:15: GPU Programming with Julia
13:30 - 15:00: Domain-Specific Applications and Case Studies
15:15 - 16:45: Final Project and Group Presentations
Setup Instructions
Option 1: Local Installation
bash
# Install Julia (if not already installed)
# Visit https://julialang.org/downloads/ and follow instructions for your OS

# Clone this repository
git clone https://github.com/nusc-summer-school/scientific-computing-julia.git
cd scientific-computing-julia

# Start Julia
julia

# In the Julia REPL, press ']' to enter the package manager
# Then install the required packages:
activate.
instantiate
Option 2: Using JuliaHub
Create an account on JuliaHub
Start a new notebook
Clone this repository or upload the materials
Option 3: Using Binder


Click the Binder badge above to launch a ready-to-use environment in your browser.

Repository Structure
scientific-computing-julia/
├── data/                   # Datasets used in the workshop
├── notebooks/              # Jupyter notebooks for each topic
│   ├── day1/
│   ├── day2/
│   └── day3/
├── exercises/              # Hands-on exercises
├── solutions/              # Exercise solutions
├── src/                    # Julia source code and modules
├── presentations/          # Slide decks in PDF format
├── projects/               # Final project templates
├── environment.yml         # Conda environment file
├── Project.toml            # Julia package dependencies
├── Manifest.toml           # Julia package versions
└── README.md               # Workshop information


Example Applications
This workshop includes the following application examples:

Climate Model Simulation: Solving PDEs for atmospheric dynamics
Quantum Physics Simulations: Quantum mechanics and many-body physics
Computational Biology: Reaction-diffusion systems and pattern formation
Financial Modeling: Option pricing and risk analysis
Resources


Recommended Reading:
Bezanson, J., Edelman, A., Karpinski, S., & Shah, V. B. (2017). Julia: A Fresh Approach to Numerical Computing. SIAM Review.
Lauwens, B., & Downey, A. B. (2019). Think Julia: How to Think Like a Computer Scientist. O'Reilly Media.
Sengupta, A., & Edelman, A. (2019). Julia High Performance. Packt Publishing.
Online Resources
Julia Documentation
Julia Academy
JuliaHub
Discourse Forum
Instructors
Dr. Maria Gonzalez - Computational Scientist, Harvard University
GitHub | LinkedIn
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
We thank all contributors and the NUSC Summer School organising committee for making this workshop possible.

For questions or additional information, please contact us at info@nuscsummerschool.edu

