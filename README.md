# How to download or install
There are several ways to use the compendium’s contents and reproduce
the analysis:

  - **Download the compendium as a zip archive** from this [GitHub
    repository](https://github.com/manika-lamba/gender/archive/main.zip).
    
      - After unpacking the downloaded zip archive, you can explore the
        files on your computer.

  - **Reproduce the analysis in the cloud** without having to install
    any software. The same Docker container replicating the
    computational environment used by the authors can be run using
    BinderHub on [mybinder.org](https://mybinder.org/):
    
      - Click
        **RStudio**: [![Binder](http://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/manika-lamba/gender/main?urlpath=rstudio) to launch an interactive 
        [RStudio](https://rstudio.com/) session in your web browser. In the virtual environment, open the `coding_shiny_app.R` file run the code.
        
       - Click
        **RShiny**: [![Binder](http://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/manika-lamba/gender/main?urlpath=shiny/gender/)
        to launch an interactive [RShiny](https://shiny.rstudio.com/) session in your web browser using [R](https://cloud.r-project.org/index.html) kernel. When you execute code within the notebook, the results appear beneath the code.
        
       - **Limitations of Binder**
         1. The server has limited memory so you cannot load large datasets or run big computations.
         2. Binder is meant for interactive and ephemeral interactive coding so an instance will die after 10 minutes of inactivity.
         3. An instance cannot be kept alive for more than 12 hours.
