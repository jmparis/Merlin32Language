## Merlin32Language for Visual Studio 2017
### https://github.com/OlivierGuinart/Merlin32Language

### Changes, August 25th, 2017

a. Run a one step migration of the Solution under VS2017

b. inside project properties (Alt-Enter), got to "Assembly Information..." and set the "Assembly version" and "File version" to 1.2.0.0

c. inside project properties (Alt-Enter), select "Target Framework" to .NET Framework 4.6.1

d. inside project properties (Alt-Enter), goto the Debug section, browse for devenv.exe.

e. CompletionController.cs

   replace SVsServiceProvider by ServiceProvider

f. source.extension.vsixmanifest

Version: 1.1 --> 1.2

Install Targets:

  Microsoft.VisualStudio.Pro   [15.0,16.0]

  Microsoft.VisualStudio.IntegratedShell   [15.0,16.0]

  Microsoft.VisualStudio.Community   [15.0,16.0]

  Microsoft.VisualStudio.Enterprise   [15.0,16.0]   

Dependencies

  Microsoft .NET Framework   Manual  4.6

Prerequisites

  Visual Studio core editor   [15.0.26606.0,16.0]

g. References

Add Microsoft.VisualStudio.Shell.Framework  15.0.0.0



