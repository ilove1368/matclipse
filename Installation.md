## Update site ##

Add http://matclipse.eclipselabs.org.codespot.com/git.update/ to the update sites in Help -> Install New Software and install Matclipse. For Windows systems, you need to install the win32 extras too.

IMPORTANT (Linux/MacOS): The Matlab path is not set at the first start, you need to set it in Window->Preferences

## From source ##

The plugins are available in the Git repository: https://code.google.com/a/eclipselabs.org/p/matclipse/source/checkout

To build the plugin yourself in Eclipse, you need the Eclipse, the PDE and the EGit plugin, which is available in the update manager. (The Eclipse Classic SDK includes PDE). Then you need to do the following steps:

1) Open perspective "Git Repository Exploring" and pull the repository from the URL https://code.google.com/a/eclipselabs.org/p/matclipse/

2) Open the Java perspective, right click one plugin and click "Run as Eclipse Application"

To run matclipse on win32, you need com.jacob, which is also included in the source repository. This plugin is not necessary on other systems.

You should get a new Eclipse instance with the matclipse plugin running inside.

IMPORTANT (Linux/MacOS): The Matlab path is not set at the first start, you need to set it in Window->Preferences

You can then switch to the Matlab Workbench perspective and start working!

For instructions how to include a plugin into the running Eclipse environment, see http://www.vogella.de/articles/EclipsePlugIn/article.html#deployplugin