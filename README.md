# Virtual environment for numpy version 1

Steps:

1. Install [Git](https://git-scm.com/downloads). You can check if it is already installed by typing `git` in a terminal.
2. Install [VSCode](https://code.visualstudio.com/) and open it.
3. Press `Ctrl`/`Cmd` + `Shift` + `p` to open a command palette and start select `Terminal: Create New Terminal`.
4. Click on the arrow next to the `+`-icon and make sure to select `Bash` (or `Git Bash` on Windows).
5. Type the following:
    ```sh
    git clone https://github.com/agdestein/numpy1
    cd numpy1
    python3 -m venv myenv
    source myenv/bin/activate
    pip3 install -r requirements.txt
    ```
6. Press `Ctrl`/`Cmd` + `Shift` + `p` and then `File: Open folder...` and then `numpy1`.
7. Click on `Extensions` in the left panel and install `Jupyter`.
8. Open the file explorer in the left panel and open `main.ipynb`.
9. Click `Select kernel` in the top-right and choose `Python environments...` and then `myenv`.
10. Start running the notebook.
