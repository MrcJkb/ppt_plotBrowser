# ppt_plotBrowser
A similar tool to the Matlab plotbrowser inteded for the quick creation of images for PowerPoint animations.

To start the GUI, call

  plotBrowser;
  
  plotBrowser(h); % on figure handle h

  p = plotBrowser(_); % to return a plotBrowser object that contains a cell array of the figure's children and sub-children.


NOTE: To use the export feature, the printfig function is required, which can be downloaded from here:

	https://github.com/MrcJkb/printfig.git