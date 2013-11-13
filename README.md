StealFocus Build
================
Re-usable build scripts. For examples, please look at the following:
- [For simple .NET solutions](https://github.com/AcmeCorp/SimpleBuildSample)
- [For ASP.NET solutions (including ASP.NET MVC and WCF)](https://github.com/AcmeCorp/AspNetBuildSample)
- [For Azure solutions](https://github.com/AcmeCorp/AzureBuildSample)
- [For BizTalk solutions](https://github.com/AcmeCorp/BizTalkBuildSample)

Downloading
-----------
You can download the application from NuGet: [http://nuget.org/packages/StealFocus.Build](http://nuget.org/packages/StealFocus.Build)

Help
----
Contact the mailing list:
- <StealFocus-Build@yahoogroups.co.uk>
- [http://uk.groups.yahoo.com/group/StealFocus-Build](http://uk.groups.yahoo.com/group/StealFocus-Build)

You can see build status here: [http://build01.stealfocus.co.uk/ccnet/ViewFarmReport.aspx](http://build01.stealfocus.co.uk/ccnet/ViewFarmReport.aspx)


To Do In This Branch
--------------------
- [ ] StyleCop.MSBuild nuget package (has project-level csproj xforms, not compatible with self-defined .proj files...)
- [ ] MSBuild.Extension.Kit nuget package
- [x] Do something about keeping these references up to date when NuGet updates to latest version or lock into a very specific version.  Maybe something like this: http://danlimerick.wordpress.com/2011/10/01/getting-around-nugets-external-package-dependency-problem/ or some PoSh magic (reading packages.config maybe?)
Is this useful? http://www.nuget.org/packages/BuildTools.MsBuild/, which builds upon: http://msdn.microsoft.com/en-us/library/microsoft.build.evaluation.projectcollection(v=vs.121).aspx
