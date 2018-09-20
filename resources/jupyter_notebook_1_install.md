# Jupyter Notebook:  Getting Started
The Jupyter notebook is an interactive computational environment, in which you can combine code, execution, rich text, mathematics, plots and rich media. 

---

### [Install the Notebook](http://jupyter.readthedocs.io/en/latest/install.html)
Installing Jupyter using Anaconda and conda:  
For new users, we highly recommend [installing Anaconda](https://www.continuum.io/downloads). Anaconda conveniently installs Python, the Jupyter Notebook, and other commonly used packages for scientific computing and data science.  (Prereq: Python is installed.)

Once anaconda is installed, you can launch the notebook by typing
```{bash}
$ jupyter notebook
```

### Upgrade all libraries/packages
We will now update all the packages/libraries installed by anaconda to ensure you have the latest version of everything!

```{bash}
$ conda update --all
```

### Run the Notebook at Terminal Prompt  
Note:  The notebook will open at the directory in which you launch the notebook on your terminal.  
```
$ jupyter notebook
```
>my example
```console
Paskins-MacBook-Pro:~ paskin$ jupyter notebook
[I 18:32:13.166 NotebookApp] JupyterLab extension loaded from /Users/paskin/anaconda3/lib/python3.6/site-packages/jupyterlab
[I 18:32:13.166 NotebookApp] JupyterLab application directory is /Users/paskin/anaconda3/share/jupyter/lab
[I 18:32:13.172 NotebookApp] Serving notebooks from local directory: /Users/paskin
[I 18:32:13.172 NotebookApp] The Jupyter Notebook is running at:
[I 18:32:13.172 NotebookApp] http://localhost:8888/?token=16855d549d1387fde686bd9269ea75230a0d425a1c5a799d
[I 18:32:13.172 NotebookApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).
[C 18:32:13.173 NotebookApp] 
    
    Copy/paste this URL into your browser when you connect for the first time,
    to login with a token:
        http://localhost:8888/?token=16855d549d1387fde686bd9269ea75230a0d425a1c5a799d
[I 18:32:13.871 NotebookApp] Accepting one-time-token-authenticated connection from ::1

```

### Shut Down the Juypter Notebook App
At terminal prompt:  
 * control + c
 * type:  `y`
 
>my example 
```console
^C[I 18:32:53.922 NotebookApp] interrupted
Serving notebooks from local directory: /Users/paskin
0 active kernels
The Jupyter Notebook is running at:
http://localhost:8888/?token=16855d549d1387fde686bd9269ea75230a0d425a1c5a799d
Shutdown this notebook server (y/[n])? No answer for 5s: resuming operation...
y
^C[I 18:33:09.698 NotebookApp] interrupted
Serving notebooks from local directory: /Users/paskin
0 active kernels
The Jupyter Notebook is running at:
http://localhost:8888/?token=16855d549d1387fde686bd9269ea75230a0d425a1c5a799d
```

---

### Getting to Know Jupyter

You can try out Jupyter on a browser without installing it.  
https://try.jupyter.org/

