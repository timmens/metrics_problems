# Metrics Problem Sets Solutions

[![Contributors][contributors-badge]][contributors-url]
[![Black Code Style][black-badge]][black-url]

## Contents

- [Software Requirements](#software-requirements)
- [How to Contribute](#how-to-contribute)
- [Problem Set 1](#hand-out-4)

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

## Hand Out 4

<a href="https://nbviewer.jupyter.org/github/timmens/metrics_problems/blob/main/handout4.ipynb"
   target="_parent">
   <img align="center" 
  src="https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.png" 
      width="109" height="20">
</a>

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/timmens/metrics_problems/main?filepath=handout4.ipynb)


The solution to the computation exercises in the fourth hand out can be found in the
notebook ``handout4.ipynb``. You can view it [here](https://nbviewer.jupyter.org/github/timmens/metrics_problems/blob/main/handout4.ipynb)
and you can play around with it online (that is, without having to install all the
packages on your local machine) [here](https://mybinder.org/v2/gh/timmens/metrics_problems/main?filepath=handout4.ipynb);
note that building the notebook can take a while (up to 5 minutes or so).

[contributors-badge]: https://img.shields.io/github/contributors/timmens/metrics_problems
[contributors-url]: https://github.com/timmens/metrics_problems/graphs/contributors
[black-badge]:https://img.shields.io/badge/code%20style-black-000000.svg
[black-url]:https://github.com/psf/black
