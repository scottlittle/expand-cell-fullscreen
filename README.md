# expand-cell-fullscreen
A Jupyter notebook extension to expand Jupyter notebook cell to entire screen.  Select a cell, click the fullscreen button and the entire cell is fullscreen!

# Install
1. Clone or download this repository: <br>
    ```
    git clone https://github.com/scottlittle/expand-cell-fullscreen
    ```
2. Install extension using a similiar command: <br>
    ```
    jupyter nbextension install expand-cell-fullscreen --sys-prefix [--symlink]
    ```
<br> You can use the option ```--symlink``` if you don't want Jupyter to copy the files to a Jupyter data path.  Also,the option ```--sys-prefix``` will direct data and config files to be configured under the activated Python (useful for people using Anaconda and environments).  See the [nbextension docs](http://jupyter-notebook.readthedocs.io/en/latest/extending/frontend_extensions.html) for more information on these options and other useful info on nbextensions.
3. Enable extension using a similar command: <br>
    ```
    jupyter nbextension enable expand-cell-fullscreen/main --sys-prefix
    ```
    <br>
4. Start ```jupyter notebook```, select a cell and click on button that says "expand cell to fullscreen" on mouseover.
5. Fullscreen!

# Uninstall
Uninstall extension using a similar command: <br>
```
jupyter nbextension uninstall expand-cell-fullscreen --sys-prefix
```
# To-Do
- Add more buttons to control what is fullscreened (whole cell or just output).
- Preserve and restore CSS after fullscreen (right now, I am just making background 'white').
- Add zoom control when in fullscreen mode.

# About

This is my first Jupyter notebook extension and sort of my first dive into Javascript.  The extension is simple enough that I hope it helps newcomers to extensions like me.  It's really just a first step into what I want to do with fullscreen.  I started [here](https://github.com/nikhilkalige/plotly-fullscreen) to make Plotly graphs fullscreen, but that it did not expand a cell to the entire fullscreen.  If you are looking to make Plotly graphs fullscreen, using my extension with the [Plotly-Fullscreen](https://github.com/nikhilkalige/plotly-fullscreen) extension will get you all the way there. Random tip: ```jupyter --paths``` reveals where the data and config files go for Jupyter notebook.  If you snoop around in those folders and files long enough, you'll probably find what you're looking for.  Let's just say that sometimes uninstalling an extension does not purge Jupyter's memory of it.
