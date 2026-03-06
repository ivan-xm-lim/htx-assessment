# Setup instructions

The python version required is 3.13, and the notebook was written and tested on Windows 11 in Pycharm version 2025.2.4.

(Other environments should work, but this configuration is known to run correctly.)

Run `pip install -r requirements.txt` to install all dependencies.

The CPLEX library should already be installed after running `pip install`, but if it doesn't work, 
you may need to install CPLEX Community Edition on your machine.

```
data/
 ├── Interview small data.xlsx
 └── pics/
      ├── scenario A.png
      ├── workload balancing.png
      └── average relative workload.png
```

The `/data` folder is required, as it contains all graphics used for the assessment analysis write-up, as well as the 
`Interview small data.xlsx` containing all data for the optimisation.

It should also contain `/pics`, which has the three `.png` graphs used in the analysis write-up.

Once everything has been cloned and installed, open the notebook (`answer.ipynb`) and run all cells; the runtime 
should be less than a minute.

Sensitivity analysis code is disabled by default because it can take 10+ minutes, depending on hardware.
