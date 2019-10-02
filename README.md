ResXFileCodeGeneratorEx2019
===========================

A VS2019 port of the ResXFileCodeGeneratorEx extension.

Original extension developed by Dmytro Kryvko (DMK Software).  More information can be found [here](http://www.codeproject.com/Articles/13830/Extended-Strongly-Typed-Resource-Generator)

The original extension has been updated for multiple versions of Visual Studio over the years.  Currently this version for VS2019 is not published in the VS Gallery.  

Previous versions can be found at


* Installing
The original project included an MSI, but installers are no longer supported in VisualStudio. Open Visual Studio as Administrator (*) and open the ResXFileCodeGeneratorEx.sln. It is grouped into Deployment and Design folders. Build the solution. This will output the files to src\ResXFileCodeGeneratorExPackage\bin\Debug. Open the ResxCodeFileGeneratorEx2019.vsix file in that folder. This will register the generator with Visual Studio.


(*) since it is building/registering a COM component.