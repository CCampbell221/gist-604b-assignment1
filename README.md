
# GIST 604B Assignment 1: GitHub Repository Management

**Student:** Courtney Campbell  
Course: GIST 604B - Open Source GIS  
Module 1: Open Source Infrastructure & Workflows  
Assignment 1: GitHub Repository Management  
University of Arizona  

## Learning Goals
In this assignment, I'm learning:
- GitHub repository management and organization
- Professional documentation with Markdown
- Writing and running Python scripts
- Using GitHub Codespaces as a cloud development environment
- Practicing the Git workflow (stage → commit → push)
- Understanding how open source projects use Issues for collaboration

## Repository Purpose
This repository demonstrates GitHub skills including:
- Creating and organizing a professional project structure
- Writing clear technical documentation
- Executing Python code in GitHub Codespaces
- Using Git for version control
- Creating labeled Issues to model collaborative workflows

## Repository Structure
- `docs/` - documentation
- `scripts/` - Python scripts

## Installation and Setup

This project has no external Python dependencies. You need Python 3 and Git.

1. Clone the repository:

   ```bash
   git clone https://github.com/CCampbell221/gist-604b-assignment1.git
   ```

2. Change into the project directory:

   ```bash
   cd gist-604b-assignment1
   ```

3. Confirm that Python 3 is available:

   ```bash
   python3 --version
   ```

No package installation or virtual environment is required for this project.

## Usage

Run the included greeting script from the project directory:

```bash
python3 scripts/hello.py
```

The script prints a greeting, course and student information, a University of
Arizona coordinate, and a short GIS-related message. Example output:

```text
Hello from GIST 604B!
Student: Courtney Campbell
Learning open source GIS workflows with GitHub
University of Arizona coordinates: 32.2319° N, 110.9501° W
I'm interested in using GIS to analyze environmental hazards and support community planning.
Updated in Codespaces
```

## Verification

To check that the script compiles without errors:

```bash
python3 -m compileall -q scripts
```
