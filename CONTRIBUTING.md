# Contrubiting to OptifineInstances

## Your First Contribution

### The Libraries
There are 2 libraries included with OptiFine; the launch wrapper 
and the OptiFine library. To obtain the launch wrapper, you can 
open the installer as a zip file and extract the launchwrapper jar. 
To obtain the OptiFine library, you have to run the installer 
and extract OptiFine. Rename this file to remove `_MOD` from 
the name. This is for the sake of consistency since all the 
other releases follow this naming convention.

### The Patch File
In the patch file, you will need to change the path to the 
library files and update the patch version. The patch version 
should be the major version of OptiFine (e.g. HD Ultra F3, 
HD Ultra F2).

### The mmc-pack.json File
This file stores a cache of patch versions. If the 
version changes for some reason (e.g. 1.14.3 to 1.14.4), you 
will need to manually change the version in this file. If these 
don't match the patch versions, MultiMC will refuse to launch 
the instance.

## Releases
Releases will be created by me after the instance is merged 
into the repository. The patch zip and instance zip will be 
created and added to the release.
