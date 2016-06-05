allskyr
=======

Author: Alex McIntosh
---------------------
Based on programs from the College of Saint Benedict 
----------------------------------------------------
and Saint John's University
---------------------------

Welcome to the allskyr project. This project includes R functions and an 
accompanying Shiny app for determining the radiant of meteor showers detected
by Rob Wyrek's ASGARD software. In particular, this project looks at data 
collected by the Saint John's University (in Collegeville, MN) allsky camera.

---
**Running the GUI:**

  The easiest way to access the GUI alone is to run the following command 
  within R:

  runGitHub("allskyr", "Mcintalmo")
  
GUI Options:
  
  **Shower Name:** Name of the meteor shower you would like to see.
    *Default: Quadrantids*
    
  **Year:** Year of the meteor shower you would like to see.
    *Default: 2009*
    
  **Remove Outliers:** Check this if you would like to remove outlying events 
    from the plot. WANRING: Can take up to 30 seconds to generate a large
    meteor shower.
    *Default: Unchecked*
    
  **IQR:** Strictness of outlier detection. Smaller numbers remove more events.
    *Default: 1.5*
    
  **Number of Bins:** Number of bins to be used for determining the shower 
    radiant.
    *Default: 25*
    
  **Generate Plot:** Generate the plot given the input provided.
  
New Class:
  **Event** - Holds information pulled from event files

Included Functions:

  BASH: 
    txt_rsync.sh - Syncs SJU events to the current working directory.
  
  R:
    **ensure.package** - Ripped straight from Introduction to Data Science by 
      Jeffrey M. Stanton

      
    
  