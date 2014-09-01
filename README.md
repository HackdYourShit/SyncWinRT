SyncWinRT
=========

This project is the WinRT implementation of the Sync Framework Toolkit to enabled synchronization with WinRT or Windows Phone 8 and SQLite.

this toolkit works for :
* Windows Phone 8.0 and 8.1 (Silverlight) 
* Windows Store apps (WinRT)
* iOS (thanks to Xamarin)
* Android (thanks to Xamarin)

The Windows Phone 8.1 (WinRT) is not yet implemented, I just wait for SQLite implementation fro SQLite.org (will be available soon, imo)


Portable Class Library / SQLite 3.8.6.0
=========
This new realease implement some new features:
- Upgrade to 3.8.6.0 (SQLite version)
- Implement PCL support

The current version works for Universal Application and Windows Phone Silverlight 8


Windows Runtime 8.1 / SQLite 3.8.4.3
=========

This new release of the WinRT implementation of the Sync Toolkit will add some new features:
- Upgrade to support SQLite Version 3.8.4.3 
- Nuget package integration : http://www.nuget.org/packages/SyncClient.SQLite 
- Out of the box Platforms support (x86, x64 and ARM) 
- Using of SQLitePCL nuget package from MSOpenTech :  https://sqlitepcl.codeplex.com/ instead of SQLite-WinRT   
- Correction of a server bug occuring in batch mode and the client disconnect during process 
- Adding support for TimeSpan type (mapped to time(7) on sql server) 
- Adding events to track the synchronization process 
- Adding support for iOS and Android

Don’t forget to read the documentation tab tutorial to see how to install the toolkit :)

Introduction
=========

This version of the Sync Toolkit adds support for synchronization with WinRT and Windows Phone 8 :

![Image of Sync](http://download-codeplex.sec.s-msft.com/Download?ProjectName=syncwinrt&DownloadId=694394)


In the sources provided website, you will find 2 samples including a simple HelloWorldSync and a complete sample Fabrikam, with CRUD operations and synchronization.

Setup
=========

To create a “synchonizable application” that will work on Windows Store apps and Windows Phone 8, you will find in the documentation tab a full tutorial (still in progress)

Here is the pages from the Wiki :

1. [Installation : Get the Sync Toolkit and required SDK](https://github.com/Mimetis/SyncWinRT/wiki/01-Setup-your-sync-scenario-:-Server-and-Client)
2. [Generate server and client code] (https://github.com/Mimetis/SyncWinRT/wiki/02-Generate-Server-and-Client-code)
3. [Create a simple application](https://github.com/Mimetis/SyncWinRT/wiki/03-Create-a-simple-application)
4. [Create a filtered application](https://github.com/Mimetis/SyncWinRT/wiki/04-Create-a-filtered-application)
5. [How to manage conflicts](https://github.com/Mimetis/SyncWinRT/wiki/05-How-to-manage-conflicts)

If you want more information, don’t forget to check my blog :  [Msdn Mim’s blog](http://aka.ms/seb)



