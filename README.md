# Boxstarter Scripts for SharePoint Development Environment Configuration

Use these configuration files with [Boxstarter](http://boxstarter.org/) and its [web launcher technique](http://boxstarter.org/WebLauncher).


## How to use

Simply open up Internet Explorer and hit "http://boxstarter.org/package/nr/url?" appended with the path to one of the above configuration files (using the raw path). This will kick of the download of an auto-generated installer that will go through and install the components from the configuration file one by one. For example:

		http://boxstarter.org/package/nr/url?https://github.com/habaneroconsulting/boxstarter-scripts/raw/master/dev.txt

*Note:* You may need to disable Internet Explorer Enhanced Security Configuration for this to work.


## Boxstarter Scripts

**dev.txt**: Simple environment script for installing browsers, Fiddler, Notepad++, NodeJS, and change some annoying windows configurations (i.e. disable UAC, enable remote desktop)

	http://boxstarter.org/package/nr/url?https://raw.githubusercontent.com/habaneroconsulting/boxstarter-scripts/master/dev.txt


**dev-sp.txt**: Same as above, but with additional SharePoint specific installations

	http://boxstarter.org/package/nr/url?https://raw.githubusercontent.com/habaneroconsulting/boxstarter-scripts/master/dev-sp.txt


**dev-sp-vs2012.txt**: Includes installations for environments with Visual Studio 2012 already installed. ASP.NET web tools and [Web Essentials 2012](http://visualstudiogallery.msdn.microsoft.com/07d54d12-7133-4e15-becb-6f451ea3bea6) extension.

	http://boxstarter.org/package/nr/url?https://raw.githubusercontent.com/habaneroconsulting/boxstarter-scripts/master/dev-sp-vs2012.txt


**dev-sp-vs2013.txt**: For installations with Visual Studio 2013 installed.

	http://boxstarter.org/package/nr/url?https://raw.githubusercontent.com/habaneroconsulting/boxstarter-scripts/master/dev-sp-vs2013.txt


**dev-sp-vs2013u4.txt**: For installations with Visual Studio 2013 Update 4 installed.

	http://boxstarter.org/package/nr/url?https://raw.githubusercontent.com/habaneroconsulting/boxstarter-scripts/master/dev-sp-vs2013u4.txt