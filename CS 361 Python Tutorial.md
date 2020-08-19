## Environment Setup

Although this class does not have intensive programming problems, it is still highly recommended to set up your Python environment before the class starts. The instructions below are just some recommendations. You are definitely welcomed to use your existing environment or set up your environment in your preferred way. You should be fine as long as you have `Python` environment, `matplotlib`, `NumPy`, `pandas`, `seaborn`, and `scikit-learn` installed. We will also need to use `PyTorch` for a bit in the final project but we don't have to set up any GPU acceleration because the computation is not very intensive.

### [Anaconda](https://www.anaconda.com/products/individual)

We highly recommend using `Anaconda`, a `Python` distribution designed for data science, because it provides us with a separate Python environment and has the basic packages we need installed. The installation process is straight-forward. You can checkout the official document for installing `Anaconda` on [Linux](https://docs.anaconda.com/anaconda/install/linux/), [Windows](https://docs.anaconda.com/anaconda/install/windows/), and [macOS](https://docs.anaconda.com/anaconda/install/mac-os/).  Before we move on, there are a couple of things we need to pay attention to.

+ If you have multiple `Python` installed (some Linux distributions come with both `Python2` and `Python3`), pay attention to which Python you are using.
+ The Windows version of `Anaconda` does not recommend adding `Anaconda` to the `PATH` environment variable. In this case, we need to open `Anaconda (64-bit)` in the start menu and use `Anaconda` related commands.
+ Initialize `Anaconda` in your shell's startup script upon installation or using `Anaconda` in a certain shell environment for the first time. There will be prompt with instructions.

### [Google Colab](https://colab.research.google.com/)

Google Colab provides us with an interactive Python notebook environment with relevant packages installed. It is sufficient for completing this course's programming problems but please note that Google Colab will take back its allocated resources for a certain (unknown) amount of time. Therefore, it's really important to save your work locally. (The final outputs of the notebook will be saved but all the variables and files will be deleted). To get permanent storage, we can [mount our Google drive to Colab](https://colab.research.google.com/notebooks/io.ipynb).