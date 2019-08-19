Behrad Borhani

This is a .Net Core 2.2 Application
navigate to the launchSettings.json file to set the GET parameters

By default they are (line 23):
 "launchUrl": "api/routes/FindRoutes/YYZ/YVR",
 
Note: First param is the origin and the second mandatory param is the destination
 

Make sure the Routes.API runs in order to see the expected results starting up with Routes.API (not IIS)

Best to run this with Visual Studio > 2017