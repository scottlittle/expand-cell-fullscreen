# expand-cell-fullscreen
A Jupyter notebook extension to expand Jupyter notebook cell to entire screen.  Select a cell, click the fullscreen button and the entire cell is fullscreen!

# Installation
1. Clone or download this repository.
2. Install extension using similiar command: <br>
    ```
    jupyter nbextension install expand-cell-fullscreen --sys-prefix [--symlink]
    ```
<br> You can use the option ```--symlink``` if you don't want Jupyter to copy the files to a Jupyter data path.  Also,the option ```--sys-prefix``` will direct data and config files to be configured under the activated Python (useful for people using Anaconda and environments).
3. Enable extension using similar command: <br>
    ```
    jupyter nbextension enable expand-cell-fullscreen/main --sys-prefix
    ```
    <br>
4. Select cell and click on button that says "expand cell to fullscreen" on mouseover.
5. Fullscreen!

# About
This is my first Jupyter notebook extension and sort of my first dive into Javascript.  The extension is simple enough that I hope it helps newcomers to extensions like me.  It's really just a first step into what I want to do with fullscreen.  I started [here](https://github.com/nikhilkalige/plotly-fullscreen) to make Plotly graphs fullscreen, but that it did not expand a cell to the entire fullscreen.  If you are looking to make Plotly graphs fullscreen, using my extension with the [Plotly-Fullscreen](https://github.com/nikhilkalige/plotly-fullscreen) extension will get you all the way there. Random tip: ```jupyter --paths``` reveals where the data and config files go for Jupyter notebook.  If you snoop around in those folders and files long enough, you'll probably find what you're looking for.  Let's just say that sometimes uninstalling an extension does not purge Jupyter's memory of it.
