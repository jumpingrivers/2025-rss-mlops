# MLOps: Automating the Machine Learning Stack

Materials for the MLOps workshop given by Myles at the RSS Internation Conference 2025.

Workshop length: 80 minutes

## Contents

Open the index.html in the browser to view the workshop slides.

R and Python variants of the demo and exercises are provided in the scripts/ folder.

## Dependencies

### R

Please run the following code in your RStudio:

```
install.packages("drat")
drat::addRepo("jr-pkg", "https://r-pkgs.jumpingrivers.training/")
install.packages("jrNicdVetiver")
```

This will automatically install {vetiver}, {tidymodels}, {pins}, {plumber} and the other R packages covered during the workshop.

### Python

Install the **jrmlops** package:

```
pip install jrmlops
```

This will automatically install vetiver, scikit-learn, pins and other packages covered during the workshop.

