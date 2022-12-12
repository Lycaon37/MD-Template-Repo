# Contributing

When contributing to this repository, please first discuss the change you wish to make via issue, email, or any other method with the owners of this repository before making a change.

## Development environment setup

To set up a development environment, please follow these steps:

1. Clone the repo

   ```sh
   git clone https://github.com/GITHUB_USERNAME/REPO_SLUG
   ```

2. Install [Cobra Tools](https://github.com/OpenNaja/cobra-tools/tree/a030a334). This link connects to the version of Cobra Tools used for this mod. Different versions may not be compatible. The following is a copy of the installation instructions from the Cobra Tools repository:
   1. Get the latest source code [here](https://github.com/OpenNaja/cobra-tools/archive/a030a334.zip) and unzip to a folder of your choice. 
   2. You need to have installed:
      - [Python 3.7 x64 bit](https://www.python.org/downloads/windows/) (**make sure you add it to the system path during installation;** 32 bit versions of python will hit their memory limit trying to read large OVLs, so 64b is recommended.)
      - [Microsoft Visual C++ Redistributable 2017 x64](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads) (needed for texture conversion - you will likely have this installed already)
      - [Microsoft Visual C++ Redistributable 2013 x86](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads) (needed for lua decompile - x86 version for now)
      #### Install python dependencies
      - open a command shell and execute the following line: 
      ```
      pip install pyqt5 imageio
      ```  
      In case this commands tells you upgrade pip, follow the instructions and then try again until all the requirements are met.
3. Install [Blender 3.20+](https://www.blender.org/)
   1. Click on "Download Blender".
   2. Click the download button in the center of your screen.
   3. Follow the instructions from the installer.
4. Install the Cobra Tools plugin for Blender.
   1. Within Blender 3.20+, click "Edit".
   2. Within the "Edit" context menu, click "Preferences".
   3. Within preferences, click "Add-ons", along the left side.
   4. Click "Install...", in the Upper-Right corner, next to "Refresh".
   5. Click on the downloaded .zip for Cobra Tools downloaded previously.

## A few notes on editing the project:

For FDB edits, please view the [documentation.](fdb-edits.md) This will provide a list of all changes made to FDB entries alongside their original values.\
To create LODs, simply press the "Create LODs", under "Cobra Mesh Tools", within Object Data Properties.

Whenever you edit the model, you should regenerate the fur to match the new model. To do this:
1. Click "Gauge UV Scale", under "Cobra Mesh Tools", within Object Data Properties.
2. Select the model and press the "N" key to pull up the model properties, under the drop-down menu at the bottom.
3. Replace uv_scale_x and uv_scale_y with the values listed within [the file on uv scales](uv-scales.md), if needed.
4. Click "Create Fins" to generate fur.

## Issues and feature requests

You've found a bug in the mod, a mistake in the documentation or maybe you'd like a new feature? You can help us by [submitting an issue on GitHub](https://github.com/GITHUB_USERNAME/REPO_SLUG/issues). Before you create an issue, make sure to search the issue archive -- your issue may have already been addressed!

Please try to create bug reports that are:

- _Reproducible._ Include steps to reproduce the problem.
- _Specific._ Include as much detail as possible: which version, what happened before the bug, etc.
- _Unique._ Do not duplicate existing opened issues.
- _Scoped to a Single Bug._ One bug per report.

**Even better: Submit a pull request with a fix or new feature!**

### How to submit a Pull Request

1. Search our repository for open or closed
   [Pull Requests](https://github.com/GITHUB_USERNAME/REPO_SLUG/pulls)
   that relate to your submission. You don't want to duplicate effort.
2. Fork the project
3. Create your feature branch (`git checkout -b feat/amazing_feature`)
4. Commit your changes (`git commit -m 'feat: add amazing_feature'`) PROJECT_NAME uses [conventional commits](https://www.conventionalcommits.org), so please follow the specification in your commit messages. A [guide to using conventional commits](conventional-commits.md) is included.
5. Push to the branch (`git push origin feat/amazing_feature`)
6. [Open a Pull Request](https://github.com/GITHUB_USERNAME/REPO_SLUG/compare?expand=1)
