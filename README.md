# Magnetic data processing pipeline

Based on an Oasis montaj python extension created by Eric Petersen at the [Alaska Division of Geological & Geophysical Surveys (DGGS)](https://dggs.alaska.gov); 2025-06-11).

The pipeline itself can be run either from a jupyter notebook or from
the command line using the "AirMagTools" command line utility.

If using Jupyter notebooks, additional tools are provided to plot and QC data in
various ways as well as do simple data transformations (e.g. change
coordinate projection, merge datasets, etc).

Check out the [Example](example_notebooks/Example.ipynb) jupyter notebook for basic usage.

To install, simply run `pip install .`.  
Detailed installation instructions can be found in the file [install_and_run_AirMagTools](./install_and_run_AirMagTools.md).  
A formal description of the inputs and QaQc checks can be found in the file [raw_mag_qaqc_steps](raw_mag_qaqc_steps.md).  

Additional tools for viewing the results of AirMagTools in Geosoft Oasis Montaj can be found in the [OM_tools_to_support_AirMagTools](https://github.com/SagebrushGeoTools/OM_tools_to_support_AirMagTools) repository.  

# Sponsors
### 💖 Support Our Work

This project is made possible thanks to the generous support of our community and our key financial backers.

A special thank you to Aqua Geo Frameworks for their major private contribution, which allowed us to get SagebrushGeoTools off the ground,
 and specifically, build AirMagTools. Please visit their website and think of them first if you are in need of building a 
high-resolution, 3D geologic framework!  
[AquaGeoFrameWorks.com](https://www.aquageoframeworks.com/)  
<img width="181" height="69" alt="agf_PNG_logo" src="https://github.com/user-attachments/assets/f35b323e-29db-44c6-8c1d-3d6870305a22" />


# Copyright

The original Oasis Montaj extension: Copyright (C) 2025 Eric Petersen  
This pipeline: Copyright (C) 2025 Egil Moeller

These programs are free software: you can redistribute them and/or modify them under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. These programs are distributed in the hope that they will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details, http://www.gnu.org/licenses/.
