# Metrics Problem Sets Solutions

[![Contributors][contributors-badge]][contributors-url]
[![Black Code Style][black-badge]][black-url]
[![CI][ci-badge]][ci-url]

## Contents

- [Software Requirements](#software-requirements)
- [How to Contribute](#how-to-contribute)
- [Solutions](#solutions)
- [Handout 4](#handout-4)
- [Handout 5](#handout-5)
- [Handout 6](#handout-6)

## Software Requirements

If you want to run the notebooks on your local machine you need to install all packages
that are listed in the file ``environment.yml``. This works easiest when using the
[conda package manager](https://docs.conda.io/en/latest/) (or [mamba](https://github.com/mamba-org/mamba)
if you know what you're doing). Assuming you installed conda you simply open your
favorite terminal emulator and run (line by line)

```zsh
$ conda env create -f environment.yml
$ conda activate metrics
```

Now you should be able to start and execute the notebooks from inside the terminal
session.

## How to Contribute

You can contribute to this repository by uploading alternative solutions, corrected
mistakes or solutions to new exercises. Feel free to do so using the pull request
strategy. That is, after cloning the repository you create a feature branch and then on
the repository webpage you create a pull request for that feature branch. Once you are
happy with your solution you ask for a code review and we will then merge the feature
branch onto main. For any questions on this process contact [timmens](https://github.com/timmens).

## Solutions

Solutions to the computation exercises are found in the following notebooks. To view
these notebooks simply press the ``render notebook`` button. If you like to play around
with these notebooks online simply press the ``launch binder`` button (note that the
building process can take a few minutes).

### Handout 4

<a href="https://nbviewer.jupyter.org/github/timmens/metrics_problems/blob/main/handout4.ipynb"
   target="_parent">
   <img align="center" 
  src="https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.png" 
      width="109" height="20">
</a>

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/timmens/metrics_problems/main?filepath=handout4.ipynb)

### Handout 5

<a href="https://nbviewer.jupyter.org/github/timmens/metrics_problems/blob/main/handout5.ipynb"
   target="_parent">
   <img align="center" 
  src="https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.png" 
      width="109" height="20">
</a>

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/timmens/metrics_problems/main?filepath=handout5.ipynb)

### Handout 6

<a href="https://nbviewer.jupyter.org/github/timmens/metrics_problems/blob/main/handout6.ipynb"
   target="_parent">
   <img align="center" 
  src="https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.png" 
      width="109" height="20">
</a>

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/timmens/metrics_problems/main?filepath=handout6.ipynb)


[contributors-badge]: https://img.shields.io/github/contributors/timmens/metrics_problems
[contributors-url]: https://github.com/timmens/metrics_problems/graphs/contributors
[black-badge]:https://img.shields.io/badge/code%20style-black-000000.svg
[black-url]:https://github.com/psf/black
[ci-badge]: https://github.com/timmens/metrics_problems/workflows/CI/badge.svg
[ci-url]: https://github.com/timmens/metrics_problems/actions?query=workflow%3ACI
