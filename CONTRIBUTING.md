## 🦸 contributor guide

- fork and clone the repository (command below clones the original repository)

    ```bash
    git clone https://github.com/SkalskiP/top-cvpr-2025-papers.git
    ```
  
- navigate to the `automation` directory

    ```bash
    cd top-cvpr-2025-papers/automation
    ```
  
- setup and activate python environment (optional, but recommended)

    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

- install dependencies

    ```bash
    pip install -r requirements.txt
    ```

- update `data.csv` with awesome CVPR 2025 papers

- update `README.md` with the following command

    ```bash
    python automation/generate.py
    ```