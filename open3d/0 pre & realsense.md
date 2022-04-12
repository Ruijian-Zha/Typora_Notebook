# Preparation & Realsense

> Realsense 的 calibrator 要使用 USB 3.0

```python
# initial import
import open3d as o3d
import numpy as np
import copy
import os
import sys

# monkey patches visualization and provides helpers to load geometries
sys.path.append('..')
import open3d_tutorial as o3dtut
# change to True if you want to interact with the visualization windows
o3dtut.interactive = not "CI" in os.environ
```





