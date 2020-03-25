# Parami 
Repository to store and share useful files, scripts and wrappers for performance analysis with [BSC's performance analysis tools](https://tools.bsc.es/) (Paraver, Dimemas, etc.)

## Content Description
* The [cfgs](cfgs) directory contains different folders organized by topics. Each folder contains Paraver configuration files related to its topic. For example, the [cfgs/counters_PAPI](cfgs/counters_PAPI) keeps configurations displaying PAPI counters information; the [cfgs/dlb](cfgs/dlb) folder has useful configuratons for analysing [DLB](https://pm.bsc.es/dlb) events.
* The [filters](filters) directory contains .xml files to be used with the paramedir tool for filtering purposes.
* In the repository you can also find the statically compiled packages of Dimemas and Paraver for Linux_x86_64 downloaded from [BSC's tools website](https://tools.bsc.es/downloads)

Paraver's configuration files are know to be obscure for inxerperienced users. To deal with this lack of information, we will try to add a coment in each cfg/filter file with a brief description of what it does. There are many files and it is difficult to comment all them, therefore contributions to document are more than welcome.
