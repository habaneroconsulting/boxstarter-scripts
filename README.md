#Miscellaneous Boxstarter scripts for environment configuration

Use these configuration files with [Boxstarter](http://boxstarter.org/) and it's [web launcher technique](http://boxstarter.org/WebLauncher). 

Simply open up Internet Explorer and hit "http://boxstarter.org/package/nr/url?" appended with the path to one of the above configuration files. This will kick of the download of an auto-generated installer that will go through and install the components from the configuration file one by one.

*dev.txt*: Simple environment script for installing browsers, Fiddler, Notepad++, NodeJS, and change some annoying windows configurations (i.e. disable UAC, enable remote desktop)

*dev-sp.txt*: Same as above, but with additional SharePoint specific installations

*dev-sp-vs2012.txt*: Includes installations for environments with Visual Studio 2012 already installed. ASP.NET web tools and [Web Essentials 2012](http://visualstudiogallery.msdn.microsoft.com/07d54d12-7133-4e15-becb-6f451ea3bea6) extension.

*dev-sp-vs2013.txt*: For installations with Visual Studio 2013 installed.

*NOTE*: The Visual Studio installations both includes ASP.NET web tools. At the time of writing this the latest version (2013.1) isn't available through Chocolatey yet so the installer will open up and prompt that it can't find the package. You just need to search for ASP.NET web tools and install the latest version from this installer prompt.