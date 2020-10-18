## Assignment 1

This is the introductory assignment of MC920 course.
The idea is to get used with the main concepts, tools and libraries that will be used along the course.

#### Concepts

- Monochromatic image as a matrix (array of arrays)
- Intensity transformations: negative, normalization, pixels inversion and mirroring
- Brightness manipulation
- Bits slicing
- Mosaic
- Mixing 2 images

#### Libraries

- _Pillow_
- _NumPy_

#### Tools

- _VS Code_
- _Jupyter Notebook_

To open the Jupyter Notebook server, there is a VS Code `task` named `Start Jupyter` (`Ctrl + Shift + B` to select a task and run it). Or you could just type `jupyter notebook` on terminal as well.

#### Running Locally

1. Clone the repository
2. Make sure to have `Python 3` installed (version `3.7.3` was used on this project)
3. Init a `virtual environment` (use `pipenv` or `virtualenv`)
4. Enter `pip install -r requirements.txt`
5. You are good to go! Don't forget to create a folder to save the outputs.

#### Observations

All images used as input should be monochromatic, .PNG format and an 8-bit image. The results are not expected to be successful if another types of images are used as input.

All operations outputs another monochromatic image with the same size and type (8-bit).
