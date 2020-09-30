iBrew 20.20 Aye!
----------------

Yes, The last itteration of iBrew.

This version will be a final consolidation of all the feature request & bug fixes from the last couple of years.

Python 2 is end of life (EOF) thus it will complicate and break stuff.
Therefor all used packages required to install with pip are in the source folder.

New features will probably be:

* Packages are now included as backup in the distro folder
* Wifi Strength (!!!)
* Triggers can post and get, so added support for homeassistent 
  - Add to readme
* Docker container
* Fixes from Idserda, Mongey
- (Custom) Firmware uploading (!!!)
- Smartthings code



Fixes from github. Thanks to: Jeroen Idserda, Conor Mongey & Gesv
- Only switch to beans if machine is in filter mode
- Bump firmware to final version
- Make sure ‘enough water’ value uses correct switch type
- Source python version from the environment
- Exceptions should be error level
- None, not null
- Docker file
- Fix Web Server BrewHandler

