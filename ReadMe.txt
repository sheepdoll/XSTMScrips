% extract IO configurator data and create a makefile from a STM CubeMX project.

% more information can be found at http://stm32duino.com

% to use install Ghostscript 

% on OSX this is installed using mac ports also install
% an X window shell such as XQuartz.

% for Windows GhostView can be installed along with Ghostscript
% it is best to set a command line window to run the interpreter
% from as this code does not create graphics output.

% for other unix systems use apt-get to install Ghostscript
% there may be additional steps required to open an XTerm
% which is not needed for this script

% windows command line users will need to work out how to 
% set the correct interpreter paths externally before
% launching Ghostscript

% this script must be in the same folder (path) as the .ioc file
% on unix use cp to add or drag this script into the directory

% interpreter must be run from the same directory path.
% on Unix systems use cd and verify with PWD  this scrpt
% defaults the path being the same as the .ioc file


% Once the interpreter us active at the Ghostscript GS> prompt type
%(xstm) run


% default is to write the makefile script to the backchannel
% this uses color highlighting to make the comments green. 
% optionally the makefile can be written to a logfile (not fully tested.)