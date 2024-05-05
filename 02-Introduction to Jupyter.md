# 1. What is the Jupyter Notebook?
In this page briefly introduce the main components of the Jupyter Notebook environment. For a more complete overview see References.

Contents

#  [What is the Jupyter Notebook?](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html#what-is-the-jupyter-notebook)
[Notebook document](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html#notebook-document)
[Jupyter Notebook App]
[kernel](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html#kernel)
[Notebook Dashboard](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html#notebook-dashboard)
[References](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html#references)

# 1.1. Notebook document
Notebook documents (or “notebooks”, all lower case) are documents produced by the [Jupyter Notebook App](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html#notebook-app), which contain both computer code (e.g. python) and rich text elements (paragraph, equations, figures, links, etc…). Notebook documents are both human-readable documents containing the analysis description and the results (figures, tables, etc..) as well as executable documents which can be run to perform data analysis.

References: Notebook documents [in the project homepage](https://ipython.org/notebook.html#notebook-documents) and [in the official docs.](https://jupyter-notebook.readthedocs.io/en/latest/notebook.html#notebook-documents)

# 1.2. [Jupyter Notebook App](https://jupyter-notebook.readthedocs.io/en/latest/)
The Jupyter Notebook App is a server-client application that allows editing and running notebook documents via a web browser. The [Jupyter Notebook App](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html#notebook-app) can be executed on a local desktop requiring no internet access (as described in this document) or can be installed on a remote server and accessed through the internet.

In addition to displaying/editing/running notebook documents, the Jupyter Notebook App has a “Dashboard” [(Notebook Dashboard)](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html#dashboard), a “control panel” showing local files and allowing to open notebook documents or shutting down their [kernels](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html#kernel).

References: Jupyter Notebook App [in the project homepage](https://ipython.org/notebook.html) and [in the official docs](https://jupyter-notebook.readthedocs.io/en/stable/).

# [1.3. kernel](https://docs.jupyter.org/en/latest/projects/kernels.html)
A notebook kernel is a “computational engine” that executes the code contained in a [Notebook document](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html#notebook-document). The ipython kernel, referenced in this guide, executes python code. Kernels for many other languages exist [(official kernels)](https://docs.jupyter.org/en/latest/#kernels).

When you open a Notebook document, the associated kernel is automatically launched. When the notebook is executed (either cell-by-cell or with menu Cell -> Run All), the kernel performs the computation and produces the results. Depending on the type of computations, the kernel may consume significant CPU and RAM. Note that the RAM is not released until the kernel is shut-down.

[See also Close a notebook: kernel shut down.](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html#kernel-shutdown)

# 1.4. Notebook Dashboard
The Notebook Dashboard is the component which is shown first when you launch [Jupyter Notebook App](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html#notebook-app). The Notebook Dashboard is mainly used to open [notebook documents](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html#notebook-document), and to manage the running [kernels](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html#kernel) (visualize and shutdown).

The Notebook Dashboard has other features similar to a file manager, namely navigating folders and renaming/deleting files.

References: from the official docs [Opening Notebooks.](https://jupyter-notebook.readthedocs.io/en/latest/notebook.html#opening-notebooks)
References: from the official docs [Opening Notebooks](https://jupyter-notebook.readthedocs.io/en/latest/notebook.html#opening-notebooks) and [Decoupled two-process model.](https://ipython.org/ipython-doc/stable/overview.html#ipythonzmq)
