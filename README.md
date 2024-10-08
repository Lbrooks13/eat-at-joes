# Eat At Joe's
PP4 - Eat At Joe's booking system built using MVC/Python/Django

## Getting started.
This section provides instructions for setting up the development environment for the project, including Python, Django, virtual environments, and front-end dependencies such as Bootstrap using Node.js and npm.

### Prerequisites
Make sure you have the following installed before proceeding:

- Python 3.x: Install from python.org.
- Node.js & npm: Install from nodejs.org. Verify installation:
```
node --version
npm --version
```

### Steps
1. Clone the Repository
First, clone the project repository from the version control system:

```
git clone https://github.com/your-username/your-repo.git
cd your-repo
```
2. Set Up Python Virtual Environment
To keep your Python dependencies isolated, it's recommended to use a virtual environment.

On macOS/Linux:
```
python3 -m venv venv
source venv/bin/activate
```
On Windows:
```
python -m venv venv
venv\Scripts\activate
```
After activating the virtual environment, you should see (venv) in your terminal prompt.

3. Install Python Dependencies
With the virtual environment activated, install the required Python dependencies listed in requirements.txt:
```
pip install -r requirements.txt
```
This will install Django and any other backend dependencies your project requires.

4. Install Front-End Dependencies (Bootstrap)
The project uses Bootstrap for styling. You can install it using npm or yarn.

Step 4.1: Initialize npm (if not already done)
If your project doesn’t already have a package.json file, initialize it in the root of your project:

```
npm init -y
```
Step 4.2: Install Bootstrap via npm
In the root of the project (where manage.py is located), install Bootstrap and its dependencies:

```
npm install bootstrap
```
This command will create a node_modules/ directory in the project root.