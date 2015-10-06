VisualStudioFileOpenTool
========================

Tool that trying open specified file at spicified line in active Visual Studio   

	usage: <version> <file path> <line number> <column number>

	Visual Studio version                 value 
	VisualStudio 2002                     2 
	VisualStudio 2003                     3 
	VisualStudio 2005                     5 
	VisualStudio 2008                     8 
	VisualStudio 2010                    10 
	VisualStudio 2012                    12 
	VisualStudio 2013                    13 


GrepWin settings:

	VisualStudioFileOpenTool.exe 12 %path% %line% 0
	
Beyond Compare settings(Options - Open With - Command line):
	
	VisualStudioFileOpenTool.exe 12 %f %l 0
	
(I don't GrepWin or Beyond Compare so I don't know if column number makes sense.)

Inspired by http://stackoverflow.com/questions/350323/open-a-file-in-visual-studio-at-a-specific-line-number


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/diimdeep/VisualStudioFileOpenTool/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

