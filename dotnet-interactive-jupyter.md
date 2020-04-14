## How to Install .NET Interactive (Windows 10)

1. Install the [.NET Core SDK](https://dotnet.microsoft.com/download)
2. Install [Anaconda](https://www.anaconda.com/distribution/) (which installs Jupyter)
3. In a cmd console, install the dotnet interactive tool:

```cmd
dotnet tool install --global Microsoft.dotnet-interactive
```

4. In the Anaconda console, install the .NET kernel:

```cmd
dotnet interactive jupyter install
```

## Work with Jupyter Notebooks

* Get help:
```cmd
jupyter --help
jupyter notebook --help
```

* Open a blank Jupyter notebook (try the desktop app as well):
```cmd
jupyter notebook
```

## How to Install JupyterLab

1. From the Anaconda console, install JupyterLab:
```cmd
conda install -c conda-forge jupyterlab
```

2. Start JupyterLab:
```cmd
jupyter lab
```

### [Launch .NET Interactive with Binder](https://mybinder.org/v2/gh/dotnet/interactive/master?urlpath=lab)


### [Share Your Notebooks with Binder](https://github.com/dotnet/interactive/blob/master/docs/CreateBinder.md)

### [Try .NET Project](https://github.com/dotnet/try)

### Resources
* [Public Preview of PowerShell Support in Jupyter Notebooks](https://devblogs.microsoft.com/powershell/public-preview-of-powershell-support-in-jupyter-notebooks/)
* [.NET Interactive is here! | .NET Notebooks Preview 2](https://devblogs.microsoft.com/dotnet/net-interactive-is-here-net-notebooks-preview-2/)
* [Announcing .NET Interactive - Try .NET includes .NET Notebooks and more](https://www.hanselman.com/blog/AnnouncingNETInteractiveTryNETIncludesNETNotebooksAndMore.aspx)
* [Try .NET repository](https://github.com/dotnet/try)
* [.NET Interactive repository](https://github.com/dotnet/interactive)
* [Jupyter docs](https://jupyter.readthedocs.io/en/latest/)
* [JupyterLab docs](https://jupyterlab.readthedocs.io/en/stable/)
*