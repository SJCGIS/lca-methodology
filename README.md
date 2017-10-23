# Land Capacity Analysis Methodology Jupyter Notebook

## Intro

San Juan County's 2036 Comprehensive Plan update process includes a Land Capacity Analysis (LCA). Conducting a Land Capacity Analysis is an important step in determining how and what growth can be accommodated through the year 2036. The Washington State Department of Commerce indicates that the Land Capacity Analysis methodology is used to determine:

* The amount of vacant, partially-used, under-utilized lands, and redevelopment potential of build properties needed to accommodate growth, and;
* If the existing or potential Urban Growth Areas (UGAs) can accommodate twenty years of urban growth.

The [LCA.pynb](https://github.com/SJCGIS/lca-methodology/blob/master/LCA.ipynb) file in this repository is a [Jupyter Notebook](http://jupyter.org/) that shows the [Python](http://python.org) code that is used to conduct the analysis. The notebook shows the step by step process of the [Draft LCA Methodology](http://sanjuanco.com/DocumentCenter/View/13229) as applied to the Eastsound UGA and the results of the analysis.

## Install

Use the [Jupyter Installation Guide](http://jupyter.org/install.html) to install Jupyter on your computer.

1. Download the [project ZIP file](https://github.com/SJCGIS/lca-methodology/archive/master.zip) and extract it to a folder on your computer.

2. Open a Terminal (Mac/Linux) or Command Prompt (Windows) and change the directory (`cd`) to the lca-methodology-master folder on your computer. Example: `cd C:\Downloads\lca-methodology-master`.

3. Create a new [conda environment](https://conda.io/docs/user-guide/tasks/manage-environments.html#creating-an-environment-with-commands) for the lca-methodology. Example: `conda create --name lca-methodology`.

4. Activate the environment you created in step 3. See [Activating an enviroment](https://conda.io/docs/user-guide/tasks/manage-environments.html#activating-an-environment). Example `activate lca-methodology` for Windows or `source activate lca-methodology` for Mac/Linux.

5. Install the software dependencies by typing `conda env create -f environment.yml` at the command prompt and press Enter.

## Run the analysis

Be sure you've activated the environment you created above then enter `jupyter notebook` from a Terminal or Command Prompt window in the lca-methodology-master directory. This should open a webpage to the current directory. Choose the LCA.pynb file to open the analysis.

Run each step by holding Shift and pressing Enter or select "Run All Cells" from the Cells menu. Some cells may take a long time to complete. An asterisk (`*`) next to appears next to a cell that hasn't completed yet.

Many cells will return a map or table underneath that shows the results of the analysis.

## Software Used

* [Geopandas](http://geopandas.org/) library is used for analysis and maps
* [NumPy](https://docs.scipy.org/doc/numpy/index.html) library is used for multidimensional computing
* [MatPlotLib](http://matplotlib.org/) library is used for displaying maps and charts

## More info

* [Comprehensive Plan Elements](http://sanjuanco.com/1306/Comprehensive-Plan-Elements)
* [Land Capacity Analysis Story Map](http://sjcgis.maps.arcgis.com/apps/Cascade/index.html?appid=f81a3abaf81e40a494cede9b73e0c140)


## License

Copyright 2017 San Juan County GIS

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

A copy of the license is available in the repository's LICENSE file.
