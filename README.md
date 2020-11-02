# `{packrat}` demo

## Clone and restore
1) Clone this repository to get local versions of these files on your computer: `git clone https://github.com/adamkucz/packrat-demo.git`
2) Start an R session within the cloned folder (make sure your current working directory is in the same location as this README document. Then, initialize `packrat` within the directory: `packrat::init()`
   - your R session should automatically restart after this, and `.libPaths()` should be pointed to the project-specific packrat installation folders
3) `packrat::restore()` to install the packages to your own computer

## When installing new packages (or updating package versions)
To add a new package, install as your normally would (`install.packages()`). Then, take a snapshot of the packrat directories to download the source files and add the installed packages to the .lock file: `packrat::snapshot()`


