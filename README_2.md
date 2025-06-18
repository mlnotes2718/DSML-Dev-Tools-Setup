# DSML-Dev-Tools-Setup

<font color = 'red'> This document is in progress</font>

This is my notes on setting up development tools for Data Science and Machine Learning (DSML) development. It also includes essential usage. 

The development tools can be divided into the following sections:
- Programming Language : In Data Science and Machine Learning development, the most popular programming language is Python. There are also other languages such as R, Matlab and Octave. We will cover Python and R. We also give a brief coverage on Octave as some shool still teaches them in  machine learning course. Under this section, we will also introduce the basic tools and package manager.
- Programming Environment : Currently, the best practice is to create an isolated programming environment for each project. This is especially necessary for Python. In Python, besides the core programming language, there are many libraries/framework available. In machine learning, the most popular frameworks are Scikit-Learn, TensorFlow, PyTorch, Keras, NumPy, SciPy, Pandas and Matplotlib. Each framework are developed by different communities. Some framework only supported certain Python version. So we end up with the need to install different version of Python for different project. Thus the need to created isolated environment.   
- Git and Github : Git is a version control software tools that track your code changes. Github a web services that allows use to store the code remotely.
- Integrated Development Environment (IDE) : IDE is a software package that includes the tools for programming and integrating tools on managing environment, linking and syncing to Git repositories. Once we install a particular packages, we will have most of the tools available to us. 


## Python
For Mac OS and Linux system, it already comes with Python. However, if the version of the python provided does not satisfy you, than you need to install the specific version from [Python Downloads](https://www.python.org/downloads/).

Basic Python installation comes with an interpreter. Once the basic installation is done. We can either 

Common IDE for Python are as follows:

- Anaconda / Miniconda : Anaconda is the most comprehensive packages for DSML. It includes most of the tools and more. However, experienced developer find it too bloated. It is recommended for beginners and experienced develop who need to make use of most of the packages in Anaconda.
- Miniconda : Miniconda is the scaled down version of Anaconda without the GUI interface. The key difference between anaconda and Miniconda can be found at the link https://docs.anaconda.com/distro-or-miniconda/
- VS Code : VS Code is a light weight IDE that could integrate with different tools mentioned above. However, we need to manually integrate them by installing the extension. The advantage of this method is that it is light weight and highly customizable. 

