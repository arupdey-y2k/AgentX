### AgentX - AI Database Agent

This is the project repository for AgentX, an AI-powered database agent designed to assist developers with complex SQL writing and optimization in a PostgreSQL environment.

**Environment Setup (macOS with Anaconda & PyCharm)**

**Follow these steps to get your development environment ready.**

**Step 1:** Create the Project Directory

1. Create a main folder named `AgentX`.
2. Inside `AgentX`, create the sub-folders and files exactly as outlined in the project structure I provided (e.g., create an `agentx` sub-folder, inside that create `controllers`, `models`, `prompts`, etc., and place each file in its correct location).

**Step 2:** Create and Activate Anaconda Environment

1. Open your terminal.
2. Navigate to your newly created project's root directory (`cd /path/to/AgentX`).
2. Create a new Conda environment for this project. We'll use Python 3.10.

`conda create -n agentx python=3.10`


4. Activate the newly created environment:

`conda activate agentx`


Your terminal prompt should now show (`agentx`).

**Step 3:** Configure PyCharm Interpreter

1. Open the `AgentX` project folder in PyCharm.
2. Go to `PyCharm` > `Settings`... (or `Preferences`...).
3. Navigate to Project: `AgentX` > `Python Interpreter`.
4. Click the gear icon and select `Add....`
5. In the left pane, select `Conda Environment`.
6. Check `Existing environment` and PyCharm should automatically detect your `agentx` environment. If not, manually locate it in the Conda installation path (`.../anaconda3/envs/agentx/bin/python`).
7. Click `OK` to set it as the project interpreter.

**Step 4:** Install Dependencies

With the `agentx` environment active in your terminal (or using PyCharm's built-in terminal), install the required packages from `requirements.txt.`

`pip install -r requirements.txt`

**Step 5:** Add a Logo (Optional)

Place your desired logo for `AgentX` inside the `agentx/static/` directory and name it `logo.png`. A placeholder size of 100x100 pixels is recommended.

**Step 6:** Run the Application

Make sure you are in the project's root directory in your terminal.
Launch the Streamlit application:
`streamlit run agentx/app.py`


Your web browser will open with the AgentX application running.
