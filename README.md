# Version 1.1.1:
- Build with Visual Studio 2019 Professional On Windows 10 x64
- Moved to .NET 4.x, there are no Microsoft supported Window versions that cannot support .NET 4.x any longer
- Added reference to System.Web.Services to allow for interfacing with DLLs that support 

# Version 1.1:
- Build with Visual Studio 2005 SP1 Professional On Windows 7 SP1 x86
- Solve a problem that does not work on some windows (Change compile settings and use from lower .net framework (net 2.0))

# Version 1.0:
- Fix bug memory overflow
- If you need to call CLR::Call more than once now this is possible (without hang)
- Removed CLR::Destroy

# NSIS CLR Loader - v0.5

A NSIS plugin to Load CLR assemblies (.NET Framework) and run methods on classes

Currently in an early stage of development, but will be a very active project.  

You can also check out the [original source](http://nsis.sourceforge.net/Call_.NET_DLL_methods_plug-in)

