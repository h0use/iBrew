iBrew 20.20 New Vision
----------------------

Yes, The last itteration of iBrew.

This version will be a final consolidation of all the feature request & bug fixes from the last couple of years.

Python 2 is end of life (EOF) thus it will complicate and break stuff.
Therefor all used packages are in the distro folder. Unzip them in the source folder if you can not install the packages with make (or pip).

New features will probably be:

* Packages are now included as backup in the distro folder
- Wifi Strength (!!!)
- (Custom) Firmware uploading (!!!)
- Smartthings code
* Triggers can post and get, so added support for homeassistent 
  - Add to readme
* Docker container
* Fixes from Idserda, Mongey
  - Not implemented Jeroen Idserda event fix (look into that)



Fixes from github:

Jeroen Idserda
- Only switch to beans if machine is in filter mode
- Bump firmware to final version
- Make sure ‘enough water’ value uses correct switch type

Conor Mongey
- Source python version from the environment
- Exceptions should be error level
- None, not null
- Docker file

