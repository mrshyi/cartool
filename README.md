cartool
=======

Export images from OS X / iOS .car CoreUI archives. Very rough code, probably tons wrong with it, but still useful.

## How to use?

This tool can extract a .car archive: https://github.com/steventroughtonsmith/cartool

**Steps to extract archive:**

1. Once you've downloaded the zip from github, compile it in Xcode to generate the command line tool. 
2. Then expand the Products group and right click on the cartool file and locate it in finder. 
3. You can then run the tool like so:
<pre>
	open terminal
	cd /path/to/cartool
 	./cartool /path/to/Assets.car /path/to/outputDirectory
</pre>
---

**Origin from**: http://stackoverflow.com/questions/22630418/analysing-assets-car-file-in-ios