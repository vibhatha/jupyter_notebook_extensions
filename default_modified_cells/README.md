# Acknowledgement

This is an effort towards understanding Jupyter Notebook Extensions. 
The first step is learning from a good resource. So I used the following article and
Github Resources from the Author: Will Koehrsen

[Blog Article](https://towardsdatascience.com/how-to-write-a-jupyter-notebook-extension-a63f9578a38c)
[Original Source Code](https://github.com/WillKoehrsen/jupyter-notebook-extensions)

# Modified Default Cell

## Notes From the Original Author

```text
The following includes the README.md notes from the original author. 
```

Adds and runs a default cell at the top of each new notebook. 
To change the default cell, edit the `add_cell` function in the `main.js` file. 
The relevant section is
`Jupyter.notebook.insert_cell_above('code', 0).set_text(``)` 
Set the `text` to whatever you would like.
This extension also adds a button to the toolbar allowing you to insert and run the default 
cell above your current cell. This can be helpful if you open an already started notebook and notice you are missing 
some common imports. This extension is a work in progress and any help would be appreciated. 
Feel free to make contributions on GitHub or contact the author (Will Koehrsen) at wjk68@case.edu

## My Contribution

Still working on a plan to improve the work. 