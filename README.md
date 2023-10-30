# Creating a file relative path in Excel 

Using Power Query within Excel can create an issue with the link to the query breaking when moving the files to a different directory. This is because Power Query uses a fully qualified path to the data files. This technique will allow you to implement a relative path strategy so the files can be shared and / or moved to different files paths with no issues.  

The video walkthrough can be seen [here](https://youtu.be/vgK1LVmxyYc).  

**Note** Ensure your files (both .xlsx and data files) are not on a synchronized share such as OneDrive as the updates to the relative path can become "confused" and not work as expected.

