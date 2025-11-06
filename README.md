<!-- ABOUT THE PROJECT -->
## About The Project

The application offers an intuitive interface for data analysis, model training, and performance evaluation. At the same time, an R markdown pipeline version is also provided for developers to conduct customized analysis. The design of this software aims to enable talented researchers without programming expertise to fully leverage these powerful analytical methods.This repository is just a _**demo version**_. If you would like more features and a complete version of the app, please contact us.

<!-- GETTING STARTED -->
## Getting Started

To install this software, please follow the steps below.

### Prerequisites

R (version 4.4.0) and R Studio software(Strongly Recommend).

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/whan4/Basic-SMART-pred.git
   ```
2. Open R project by clicking on R.Rprofile
3. Restore R packages by renv.lock
   ```r
   renv::restore()
   ```
4. Install dependencies
   ```r
   install.packages("shiny", "rmarkdown")
   ```
5. Every time you run the app, the software will perform a self-check. If additional packages are needed, select 'y' to install them.
