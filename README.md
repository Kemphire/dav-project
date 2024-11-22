# Steps to work on this project locally

- For macos/linux
    - curl -LsSf https://astral.sh/uv/install.sh | sh
    - git clone the repo
    - cd into project
    - uv sync
    - jupyter lab

- For windows
    - powershell -c "irm https://astral.sh/uv/install.ps1 | iex"
    - git clone the repo
    - cd into project
    - uv sync
    - jupyter lab


> In case you are not willing to install **uv** then run the following commands

- first git clone the project
- cd into project
- python -m venv .venv
- For windows 
    - Scripts\Scripts\activate.bat
- For macos/linux
    - source .venv/bin/activate
- pip install -r requirements.txt
