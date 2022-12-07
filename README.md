# Getting startd with Stable Diffusion using Anaconda

This repository has been prepared using [Anaconda Project](https://anaconda-project.readthedocs.io/en/latest/), which
extends conda environments to provide cross-platform environment specifications and to launch defined commands.

This project has also been published to [Anaconda.org](https://anaconda.org/defusco/project/stable-diffusion-cpu) where you can download a Zip file or use `anaconda-project` to download and extract it.

## Setup

To download, extract, prepare, and run this project using the published archive on Anaconda.org the steps are

1. Download and install [Anaconda Distribution](https://www.anaconda.com/products/distribution)
1. Launch the terminal
    * On MacOS you can launch the Terminal app from your /Applications directory
    * On Windows you can launch the Anaconda Prompt from the Start Menu
1. In the terminal download and extract the project by running
    ```
    anaconda-project download defusco/stable-diffusion-cpu
    ```
1. Move into the project directory install the conda environment and launch Jupyter Notebook
    ```
    cd stable-diffusion-cpu
    anaconda-project run
    ```

### Using a Github clone

If you'd rather work with a clone of this repository replace step 3 above with

```
git clone https://github.com/anaconda/stable-diffusion-cpu.git
```
