#AngularJS with Web API: server side paging

This is the source code for the MSDN sample [**AngularJS with Web API: server side paging**](https://code.msdn.microsoft.com/AngularJS-with-Web-API-43e5de16). For a full description of the code please visit the link.

##Overview

This sample shows how to create a Web API 2 controller that supports paging. It also shows two approaches to using the paging functionality with an AngularJS client.

•simple paging - show a single list of n items to the user and if more items are available allow the user to get the next page of n items until all have been returned. 
•full paging - divide the data into pages of n items. The items for each page are loaded when the page is first viewed by the user. 

Both approaches support changing the page size and sorting of the data.
