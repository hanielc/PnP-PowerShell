#Add-SPOPublishingPage
*Topic automatically generated on: 2015-10-13*

Adds a publishing page
##Syntax
```powershell
Add-SPOPublishingPage [-Title <String>] -PageName <String> -PageTemplateName <String> [-Publish [<SwitchParameter>]] [-Web <WebPipeBind>]
```


##Parameters
Parameter|Type|Required|Description
---------|----|--------|-----------
|PageName|String|True||
|PageTemplateName|String|True||
|Publish|SwitchParameter|False|Publishes the page. Also Approves it if moderation is enabled on the Pages library.|
|Title|String|False||
|Web|WebPipeBind|False|The web to apply the command to. Omit this parameter to use the current web.|
