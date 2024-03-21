# chatbot_api

Brief project description goes here.

## Setup

### 1. Setting up Python Environment

To set up a Python environment for this project, follow these steps:

1. Install [Python](https://www.python.org/downloads/) if you haven't already.
2. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/hamza-Jaral/chatbot_api.git
    ```

3. Navigate to the project directory:

    ```bash
    cd project_directory
    ```

4. Create a virtual environment. You can use `venv` (built-in with Python) or `virtualenv`:

    ```bash
    # Using venv (Python 3)
    python3 -m venv env

    # Using virtualenv
    virtualenv env
    ```

5. Activate the virtual environment:

    ```bash
    # On macOS/Linux
    source env/bin/activate

    # On Windows
    .\env\Scripts\activate
    ```

### 2. Installing Dependencies

Once the virtual environment is activated, install the project dependencies using `pip`:

```bash
pip install -r requirements.txt
```

### 3. Creating `.env` File

To create a `.env` file for configuring environment variables, follow these steps:

1. Duplicate the `env.example` file and rename it to `.env`.
2. Open the `.env` file and provide appropriate values for the environment variables as needed.


### 4. Obtaining YouTube API Key

You can obtain a YouTube API key from the [Google Cloud Console](https://console.cloud.google.com/). Follow these steps:

1. Go to the [Google Cloud Console](https://console.cloud.google.com/).
2. Sign in with your Google account or create one if you don't have it.
3. Create a new project or select an existing one.
4. Navigate to the API & Services > Credentials section from the left sidebar menu.
5. Click on the "Create credentials" button and select "API key".
6. Copy the generated API key.
7. Use this API key in your application to authenticate requests to the YouTube API.
