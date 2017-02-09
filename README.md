# expand-cell-fullscreen
Expand Jupyter notebook cell to entire screen

# Installation
1. Clone or download this repository.
2. Install extension using similiar: <br>
    ```
    jupyter nbextension install expand-cell-fullscreen --sys-prefix [--symlink]
    ```
    <br>
<br> You can use the option ```--symlink``` if you don't want Jupyter to copy the files to a Jupyter data path.  Also,the option ```--sys-prefix``` will direct data and config files to be configured under the activated Python (useful for people using Anaconda and environments).
3. Enable extension using similar: <br>
    ```
    jupyter nbextension enable expand_cell_to_fullscreen/main --sys-prefix
    ```
    <br>
4. Select cell and click on button that says "expand cell to fullscreen" on mouseover.
5. Fullscreen!
