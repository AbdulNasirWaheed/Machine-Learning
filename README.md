My Machine Learning Journey 🤖Welcome to my Machine Learning learning repository! This repo serves as a daily log, codebase, and documentation hub as I progress from foundational setups to building and deploying ML models.  📁 Repository StructureWeek-02/ (Core Curriculum & Lab Configurations)  Lecture-01/  commands.md (CLI execution logs)  test.py (Environment verification script)  🛠️ Lecture 1: Setting Up the ML Development EnvironmentThe goal of this lecture was to establish a clean, isolated local development workspace. Using virtual environments ensures that our data science packages won't conflict with global system dependencies.  🚀 Quick Start Guide1. PrerequisitesPython 3.13+ installed (Ensure Add Python to PATH is checked during installation).  VS Code text editor.  2. Setting Up the Project LocallyBash# Clone the repository
git clone https://github.com/your-username/my-ml-journey.git
cd my-ml-journey

# Create a virtual environment
python -m venv venv

# Activate the environment (Windows CMD)
venv\Scripts\activate

# Upgrade package installer
python -m pip install --upgrade pip
```[cite: 2]

### 3. Required VS Code Extensions[cite: 2]
To make development seamless, ensure the following extensions are installed:[cite: 2]
* **Python** (by Microsoft)[cite: 2]
* **Pylance** (Type checking and code analysis)[cite: 2]
* **Jupyter** (For running notebook experiments)[cite: 2]

---

## 🧪 Verification[cite: 2]
Run the validation script to verify your workspace configuration:[cite: 2]
```bash
python test.py
```[cite: 2]
**Expected Output:**[cite: 2]
> `Machine Learning Environment Ready!`[cite: 2]

## 📅 What's Next?[cite: 2]
In **Lecture 2**, we will begin installing and exploring essential data science libraries: `NumPy`, `Pandas`, `Matplotlib`, and `Scikit-learn`.[cite: 2]

---

### 3. Lecture 1's `commands.md` File[cite: 1]

# Lecture 1: CLI Command Log & Cheat Sheet[cite: 1]

This file logs the exact terminal commands used to construct and verify the Machine Learning development environment on Day 01.[cite: 1]

## 1. System Verification[cite: 1]
Check if Python and its package manager are globally accessible.[cite: 1]
```bash
python --version
pip --version
```[cite: 1]

## 2. Directory & Virtual Environment Creation[cite: 1]
Initialize the workspace directory and build an isolated python environment container.[cite: 1]
```bash
# Create and enter the project folder
mkdir my-ml-journey
cd my-ml-journey

# Generate the virtual environment folder
python -m venv venv
```[cite: 1]

## 3. Virtual Environment Activation[cite: 1]
Run the specific activation script depending on your Operating System.[cite: 1]

### Windows (Command Prompt)[cite: 1]
```cmd
venv\Scripts\activate
```[cite: 1]

### Windows (PowerShell)[cite: 1]
*Note: If script execution is blocked, run the execution policy command first.*[cite: 1]
```powershell
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
.\venv\Scripts\Activate.ps1
```[cite: 1]

### Linux / macOS[cite: 1]
```bash
source venv/bin/activate
```[cite: 1]

*Confirm activation by checking for the `(venv)` prefix in your terminal prompt.*[cite: 1]

## 4. Package Manager Upgrades[cite: 1]
Ensure the latest security and performance patches for `pip` are applied within the active environment.[cite: 1]
```bash
python -m pip install --upgrade pip
```[cite: 1]

## 5. Editor Workspace Launch[cite: 1]
Launch VS Code directly into the current initialized project directory.[cite: 1]
```bash
code .
```[cite: 1]

## 6. Environment Sanity Check[cite: 1]
Execute the local test script to confirm environment functionality.[cite: 1]
```bash
python test.py
```[cite: 1]
