To run this project successfully, it is important to install the libraries in the correct location (a virtual environment) rather than your computer's global system. This prevents version conflicts (the "Traffic Control" issue) where your computer might try to use old, incompatible tools.

### Step 1: Create the "Private" Environment
Instead of installing globally, create a local environment just for this project:

// Windows
python -m venv .venv
// Mac/Linux
python3 -m venv .venv

### Step 2: Activate the Environment
You must "enter" this environment before installing anything.

// Windows
.\.venv\Scripts\activate
// Mac/Linux
source .venv/bin/activate

Look at your terminal command line. You must see (.venv) at the very beginning of the line.

### Step 3: Install Dependencies
pip install -r requirements.txt

### Step 4: Run the App
Launch the application using the streamlint module:
python -m streamlit run ui.py