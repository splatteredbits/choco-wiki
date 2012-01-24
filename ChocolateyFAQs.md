# Frequently Asked Questions

###What is chocolatey?  
Chocolatey is kind of like apt-get, but for Windows (with windows comes limitations). It is a machine level package manager that is built on top of nuget command line and the nuget infrastructure.  
[[More behind the name|History]]

"Okay, machine package manager, that's nice. What does that mean though?" It means you can simply install software with a few keystrokes and go get coffee while your co-workers are downloading and running an install manually (and I do mean something like an MSI).  
  
How about updates? Wouldn't it be nice to update nearly everything on your machine with a few simple keystrokes? We think so, too.  Chocolatey does that.  
  
###How is chocolatey different than NuGet and/or OpenWrap?
Chocolatey is a machine package manager. Where NuGet/OW are focused on developer library packages, chocolatey is focused on applications and tools, and not necessarily developer focused.
  
###Is there a video I can watch to show me chocolatey in action?
There is! This is a long video due to slow internet connections, but watch the first 1:30ish minutes and the last 1:30ish minutes and that will give you a general idea. [http://www.youtube.com/watch?v=N-hWOUL8roU](http://www.youtube.com/watch?v=N-hWOUL8roU)  
NOTE: This video shows dependency chaining, so you are seeing it install 11 applications/tools.  
  
###What can I install?
Some chocolatey packages are tagged with chocolatey. To see what chocolatey packages are available, type `clist chocolatey`. This is not a comprenhensitve listing because not all tools add the chocolatey tag.  
  
###What kind of package types does chocolatey support?
  
* Binary Packages - Tools/Applications - This is 98% of the chocolatey packages - most are pointers to the real deal installers / zips.  
* Powershell Command Packages - Packages that have the suffix **.powershell** will install powershell scripts as commands for you to call from anywhere.
* Development Packages - Packages that have the suffix **.dev**. For instance [dropkick.dev](http://nuget.org/list/packages/dropkick.dev).
* Coming soon - Virtual Packages - Packages that are like a category, and you just want one package from that category. [Read more ...](https://github.com/ferventcoder/nugetpackages/issues/30)
  