Files
=====

To run SUSTAIN, you need to have the App files and the data files.
The App files include the SUSTAIN executable and its dependence.
The data files include the Watershed model data and MODFLOW model data.
The file structures are shown below.

App file tree:
::
  |   SUSTAIN.bat
  |
  +---main
  |   |   main.exe
  |   |   SUSTAIN dependence files

Data file structure:
::
  |   SUSTAIN namefile
  +---bin
  |   |   MODFLOW and other executables
  +---baseline
  |   |   historical simulation
  |   |   future simulation
  +---modflow
  |   |   modflow data files
  +---rswb
  |   |   watershed data fiels
  +---zones
  |   |   zone files


These are the documents for important files used by SUSTAIN.


.. toctree::
  name
  config
  exe
  *
