---
  layout: post
---

This post is a brief introduction of the tools for location cover models. Location cover models aim to locate a set of facilities in potential locations in order to maximise the coverage of demand or to minimise the facilities needed. Two representative models are the Location Set Covering Model (LSCP) and Maximum Coverage Location Model (MCLP).

These models can be found from the following software or packages.

# ArcGIS location-allocation analysis. 

This is part of the network analysis tootls in ArcGIS, and it can be used within ArcGIS Desktop or ArcPy.

See [this link](http://desktop.arcgis.com/en/arcmap/latest/extensions/network-analyst/algorithms-used-by-network-analyst.htm).

# PySpatialOpt

This is a Python package for location cover models. To use this package, you would need ArcGIS and QGIS to preprocess the data and to generate the service areas. It needs a mixed programming sovler to solve the problems, including lp_solve, Gurobi, CPLEX, XPRESS and GLPK.

See [this link](https://github.com/apulverizer/pyspatialopt).

The author is also developing a similar open-source package called [allagash](https://github.com/apulverizer/allagash). As the author said, this one is a lot refined and intergrated with Geopandas and the ArcGIS API for Python, and the documentation is much better with full Jupyter notebook examples and a Docker image. 

# Maxcovr

This is a R package for MCLP and LSCP. See [this link](https://github.com/njtierney/maxcovr) for more details.

A limitation of this package is that it only uses the Haversine distance, which is a type of the greater distance distance.

# ELP Solver

This is a Excel worksheet and is based on Visual Basic language. Like ArcGIS, it uses heuristics to solve the models, so the solutions obtained are not necessarily optimal.

See [this link](https://people.bath.ac.uk/ge277/index.php/flp-spreadsheet-solver/).

# To be continued

Recently I am writing an article on comparing these tools regarding the function and computational efficiency. I will update this blog later. 


