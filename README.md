DevReachConferenceSite
======================

### This repository is not automatically upgraded to latest Sitefintiy version. The repository is monitored for pull requests and fixes. The latest official version of Sitefinity that supports this sample is 8.2. Be aware that using a higher version could cause unexpected behavior. If you successfully upgrade the example to a greater version, please share your work with the community by submitting your changes via pull request.


[![Build Status](http://sdk-jenkins-ci.cloudapp.net/buildStatus/icon?job=Telerik.Sitefinity.Samples.DevReachConferenceSite.CI)](http://sdk-jenkins-ci.cloudapp.net/job/Telerik.Sitefinity.Samples.DevReachConferenceSite.CI/)

The DevReach sample project demonstrates how to create a simple conference site utilizing the Related Data feature capabilities in Sitefinity CMS 7.0 or later.

Using the DevReach sample, you can:

* Set up a working solution for conference site
* Create relations between different type of items
* Related items in the back end and easily display them in the front end
* View examples of RelatedData API

### Requirements

As the DevReach sample project is a simple Sitefinity 8.0 project it has the standard [system requirements](http://www.sitefinity.com/documentation/documentationarticles/installation-and-administration-guide/install-sitefinity/system-requirements-).

* Sitefinity CMS 8.0 license
* .NET Framework 4
* Visual Studio 2012
* Microsoft SQL Server 2008R2 or later versions

### Nuget package restoration
The solution in this repository relies on NuGet packages with automatic package restore while the build procedure takes place.   
For a full list of the referenced packages and their versions see the [packages.config](https://github.com/Sitefinity-SDK/Telerik.Sitefinity.Samples.DevReachConferenceSite/blob/master/SitefinityWebApp/packages.config) file.    
For a history and additional information related to package versions on different releases of this repository, see the [Releases page](https://github.com/Sitefinity-SDK/Telerik.Sitefinity.Samples.DevReachConferenceSite/releases).    


### Installation instructions: DevReachConferenceSite Sample from GitHub

1. Restore the data base of the project ('DevReach.bak') located in _SitefinityWebApp_ folder on your local server
1. In Solution Explorer, navigate to _SitefinityWebApp_ » *App_Data* » _Sitefinity_ » _Configuration_ and select the **DataConfig.config** file. 
3. Modify the **connectionString** value to match your server address and database.

### Login

To login into the Sitefinity CMS backend, use the following credentials:  
**Username:** admin  
**Password:** password

### Additional resources

#### Youtube video:   
Check the follow up [video](https://www.youtube.com/watch?v=WVKasAtZZYk) for the Sitefinity partner webinar aired on 08 April 2014.    
[![Related Content](https://raw.githubusercontent.com/Sitefinity-SDK/Telerik.Sitefinity.Samples.DevReachConferenceSite/master/EmbedVideo.png)](http://youtu.be/WVKasAtZZYk)

#### Progress Sitefinity CMS Documentation:   
Sitefinity CMS 7.0+ enables you relate content to any other content, thus relating items of different types. For  developer documentation about this powerful _Related data_ field can be at [Content relations: Related data](http://docs.sitefinity.com/content-relations-related-data).
