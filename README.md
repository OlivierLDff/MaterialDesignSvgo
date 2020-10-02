# ✒ Material Design Svgo

![Generate Svgo](https://github.com/OlivierLDff/MaterialDesignSvgo/workflows/Generate%20Svgo/badge.svg)

## Features

* This repo contains optimized svg version of icons in [Templarian/MaterialDesign](https://github.com/Templarian/MaterialDesign).
* An svg file is smaller of 30%-60% in average.
* Help reduce binary size of application embedding icons.
* The content of the repository is automatically generated every day via github action.

## Actions

* Svgs are optimized with [svgo](https://github.com/svg/svgo).
* To update the github workflow, push to a `ci` branch.
* svgo have a `-f` (folder) arguments, but it fail. That is why i'm using a for loop.