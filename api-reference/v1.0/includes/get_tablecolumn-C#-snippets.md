
```C#

GraphServiceClient graphClient = new GraphServiceClient();
var columns = await graphClient.Me.Drive.Items["{id}"].Workbook.Tables["{id|name}"].Columns["{id|name}"]
	.Request().GetAsync();

```