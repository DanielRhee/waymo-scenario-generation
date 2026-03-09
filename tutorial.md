# Python versioning
We use python3.8 packaged by anaconda. 
For lab members, in the pvc there is a setup script 'start.sh' that can be run that will create the necessary conda environments.

# Files that need modifications
```
~/persistent/conda/install/envs/CONDA-ENVIRONMENT-NAME-HERE/lib/python3.8/site-packages/waymo_open_dataset/utils/sim_agents/visualizations.py
```
Insert:
```
from typing import List
```
On line 110 change
```
-> list[patches.Rectangle]
```
to
```
-> List[patches.Rectnagle]
```
