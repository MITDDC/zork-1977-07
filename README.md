# Zork source code, 1977 June-July
This repository contains the source code and binary files for June and July 1977 versions of [Zork](https://en.wikipedia.org/wiki/Zork), an interactive fiction game created at MIT by Tim Anderson, Marc Blank, Bruce Daniels, and Dave Lebling. The files are a part of the [Massachusetts Institute of Technology, Tapes of Tech Square (ToTS) collection](https://archivesspace.mit.edu/repositories/2/resources/1265) at the MIT Libraries Department of Distinctive Collections (DDC).
## File organization and details
### [zork](../main/zork)
The files within this directory are the Zork specific files from multiple tape images from around the same time period in 1977. They are from the ```9005143.tap```, ```9005183.tap```, and ```9006255.tap``` tape image files within the ```/tots/recovered/vol2``` directory of the [ToTS collection](https://archivesspace.mit.edu/repositories/2/resources/1265). Most files are written in the MDL programming language and were originally created on a PDP-10 timeshare computer running the ITS operating system.

The files were extracted from the tape image using the [itstar program](https://github.com/PDP-10/itstar). The filenames have been adapted to Unix conventions, as per the itstar translation. The original filename syntax would be formatted like, ```MARC; ROOMS 241```, for example. All files have been placed into this artificial zork directory for organizational purposes. The files extracted from the tape images were put into sub-folders with a corresponding name to the tapes listed above.

The ```madman```, ```marc```, and ```taa``` directories in each sub-folder contain the source code and binary files for the game. Some of the files remain encrypted as found in the tape images.

The program used to start the game, ```ts.zork```, is in this [```marc```](../main/zork/9005143/marc) directory.

Files with extensions ```.nbin``` and ```.save``` are binary compiled files.

The [```ar2.tv```](../main/zork/9005143/taa/ar2.tv) file is an ITS archive file. MIT DDC digital archivist, Joe Carrano, extracted the contents of the file into the [```ar2.tv```](../main/zork/9005143/ar2.tv) folder using the [```itsarc program```](https://github.com/larsbrinkhoff/pdp10-its-disassembler/blob/master/itsarc.c). Also included is a file listing ([```ar2.txt```](../main/zork/9005143/ar2.txt)) which shows the original timestamps of the files as extracted.

### [codemeta.json](../main/codemeta.json)
This file is metadata about the Zork files, using the [CodeMeta Project](https://codemeta.github.io/) schema.
### [LICENSE.md](../main/LICENSE.md)
This file describes the details about the rights to these files. See [Rights](#rights) for additional information.
### [README.md](../main/README.md)
This file is the readme detailing the content and context for this repository.
### [tree.txt](../main/tree.txt)
A file tree listing the files in the [```zork```](../main/zork) directory showing the original file timestamps as extracted from the tape image.

## Preferred Citation
[filename], Zork source code and binary files, 1977 June-July, Massachusetts Institute of Technology, Tapes of Tech Square (ToTS) collection, MC-0741. Massachusetts Institute of Technology, Department of Distinctive Collections, Cambridge, Massachusetts. [swh:1:dir:ba6df51bcfdf51ba361bbf595332ce035a3a75f6](https://archive.softwareheritage.org/swh:1:dir:ba6df51bcfdf51ba361bbf595332ce035a3a75f6)
## Rights
To the extent that MIT holds rights in these files, they are released under the terms of the [MIT No Attribution License](https://opensource.org/licenses/MIT-0). See the ```LICENSE.md``` file for more information. Any questions about permissions should be directed to [permissions-lib@mit.edu](mailto:permissions-lib@mit.edu)
## Acknowledgements
Thanks to [Lars Brinkhoff](https://github.com/larsbrinkhoff) for help with identifying these files and with extracting them using the itstar program mentioned above.
