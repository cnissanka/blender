# bpy
Pre-built [Blender](https://www.blender.org/) 2.83 as a python 3.8 module bpy for linux.

## Dependencies
Note that this repository requires **Python 3.8**. Run [THIS](https://github.com/blender/blender/blob/master/build_files/build_environment/install_deps.sh) script to install all Blender dependencies before installing this module.
```bash
wget "https://github.com/blender/blender/blob/master/build_files/build_environment/install_deps.sh"
chmod +x install_deps.sh
./install_deps.sh
```

## Installation

```bash
git clone https://github.com/cnissanka/blender.git
python3 -m pip install path/to/cloned/repo
```

## Usage
```bash
from blender import bpy
```
