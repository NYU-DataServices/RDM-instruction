# Data Management

[![forthebadge](https://forthebadge.com/images/badges/cc-sa.svg)](https://forthebadge.com)

## About
This book contains materials for asynchronous learning of RDM best practices from NYU Data Services.

## Build our book locally
1. Fork, clone or download this project (See #1-4 in the 'Contribute!' section below)
2. Install R & RStudio
3. Install the bookdown, RMarkdown, and tinytex packages in RStudio with the following two commands in the R terminal:

    * `install.packages(c("rmarkdown", "bookdownplus", "tinytex", "webshot"))`
    * `tinytex::install_tinytex()`
    * `webshot::install_phantomjs()`

You can also click Tools > Install Packages and type the package names (make sure "install dependencies" is checked) separated by commas.

4. Go to the project folder and double click `RDM.Rproj` to start RStudio
5. Run this command in the R Console after RStudio opens: `bookdown::render_book('index.Rmd', 'all')`
6. Go to the folder `_book` in the project folder and click `index.html` to view the book locally in your browser.
                                         
## Contribute!
If you'd like to contribute, that would be amazing! We will try our best to be on top of pull requests and issues. Beforey you start, please refer to our [contributing guide](CONTRIBUTING.md). 

## Contact info
You are welcome to email me at [vicky dot steeves at nyu dot edu](mailto:vicky.steeves@nyu.edu) if you have questions or concerns, or raise an issue on this repository and I will do my best to respond quickly!
