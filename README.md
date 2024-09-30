# Virtual environment for numpy version 1

Steps:

1. Install [Git](https://git-scm.com/downloads). You can check if it is already installed by typing `git` in a terminal.
2. Install [VSCode].
3. Open a terminal.
4. Type the following:
    ```sh
    git clone https://github.com/agdestein/numpy1
    cd numpy1
    python3 -m venv myenv
    source myenv/bin/activate
    pip3 install -r requirements.txt
    ```
5. Open VSCode
6. Click `File: Open folder...` and choose `numpy1`
7. Click on `Extensions` in the left panel and install `Jupyter`
8. Open `main.ipynb`
9. Click `Select kernel` in the top-right and choose `Python environments...` + `myenv`
10. Run the notebook
