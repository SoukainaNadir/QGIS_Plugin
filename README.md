# QGIS_Plugin
It's a Python-developed QGIS plugin that features a diverse range of interfaces, including: 
1) Interface for Attribute Query
2) Interface for Spatial Query
3) Derogation Decision-Making
4) Satellite Image Downloads from SciHub Copernicus (Sentinel 2 and 3)🛰️
To ensure optimal functioning of my plugins, please install the following modules: 'tqdm' and 'sentinelsat'. You can install them by following these instructions in the PYTHON console of QGIS:
import subprocess
subprocess.run(['pip', 'install', 'sentinelsat'])
subprocess.run(['pip', 'install', 'tqdm'])

Once you have installed the plugins and modules, please open the project beforehand and then launch the plugin to avoid any "IndexError: list index out of range" errors.

