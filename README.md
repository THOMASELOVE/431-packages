# 431-packages

These instructions are meant to be used after you've completed the installation of R and RStudio, as described in [the Software section](https://thomaselove.github.io/431-2025/software.html) of [our main course website](https://thomaselove.github.io/431-2025).

## R Packages to Install for 431

An R "package" is a collection of functions, data, and documentation that extends the capabilities of R, and is the critical way to get R doing interesting work. These package instructions should be used after you've installed R and RStudio. We will add packages to this list as the semester continues.

1. Open RStudio. Copy and paste the following lines of code into the **Console** window of RStudio to install a few key packages.

```
pkgs <-  c( "broom", "car", "DescTools", "emmeans", "Epi", "fivethirtyeight",
            "GGally", "ggdist", "ggpubr", "ggstatsplot", "glue",
            "gt", "haven", "here", "infer", "janitor", "knitr",
            "medicaldata", "mice", "MKinfer", "mosaic", "naniar",
            "nhanesA", "olsrr", "palmerpenguins", "patchwork",
            "readxl", "rstanarm", "styler", "tidytuesdayR", "xfun",
            "easystats", "tidyverse" )

install.packages(pkgs)
```

2.  Execute those commands by hitting Enter.

3.  Now, go to the **Packages** tab on the right side of your RStudio screen, and click on **Update**. (This is also how you'll Update packages later this term.)

4.  This will bring up a dialog box. I usually click **Select All**, then click **Install Updates**. 
- A popup box may appear, asking "Do you want to install from sources the packages which need compilation?" to which I usually answer **No**. A **Yes** response leads to a slower installation, but can solve problems if you still have them after updating.
- This may take a few minutes. As long as you're seeing activity in the Console window, things are progressing.
- Eventually, you'll get a message that "The downloaded source packages are in ..." with a directory name. That's the sign that the updating is done.
- Updating packages is something you'll do occasionally throughout the semester, mostly when a problem happens.

5.  Finally, choose **File ... Quit Session** from the top menu, and accept or deny (I usually deny) RStudio's request to save your workspace.

### Note: A Windows Issue

If you are using Windows, and get messages during installation that the latest version of RTools needs to be installed, you can usually just ignore them. If you don't want to ignore them, [go here to download and install RTools](https://cran.r-project.org/bin/windows/Rtools/) for Windows.

### Contents of the Tidyverse and Easystats Meta-Packages

- Installing the `tidyverse` meta-package installs the packages listed at https://www.tidyverse.org/.
- Installing the `easystats` meta-package installs the packages listed at https://easystats.github.io/easystats/.

## Installing a Single Package

If you want to install a single package, you can do so by finding the word **Packages** on the right side of your RStudio screen. 

1. Click on the **Packages** tab to start installing the packages you'll need. 
2. Click **Install**, which will bring up a dialog box, where you can type in the names of the packages that you need. These should be separated by a space or comma. Be sure to leave the Install dependencies box checked.
    - A popup box may appear, asking "Do you want to install from sources the packages which need compilation?" to which I usually answer **No**. A **Yes** response leads to a slower installation, but can solve problems if you still have them after updating.
    - This may take a few minutes. As long as you're seeing activity in the Console window, things are progressing.
    - Eventually, you'll get a message that "The downloaded source packages are in ..." with a directory name. That's the sign that the updating is done.

[Click here](https://thomaselove.github.io/431-2025/) to return to the main website for the course.
