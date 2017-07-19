# WorksheetAddedEvent Object (JavaScript API for Excel)

Provides information about the worksheet that raised the Added event.

## Properties

| Property	   | Type	|Description| Req. Set|
|:---------------|:--------|:----------|:----|
|context|object|Gets the context object that facilitates requests to the Excel application.|[ApiSet.InProgressFeatures.Event](../requirement-sets/excel-api-requirement-sets.md)|
|source|string|Gets the source of the event. Possible values are: Local, Remote.|[ApiSet.InProgressFeatures.Event](../requirement-sets/excel-api-requirement-sets.md)|
|type|string|Gets the type of the event. Possible values are: WorksheetDataChanged, WorksheetSelectionChanged, WorksheetAdded, WorksheetActivated, WorksheetDeactivated, TableDataChanged, TableSelectionChanged.|[ApiSet.InProgressFeatures.Event](../requirement-sets/excel-api-requirement-sets.md)|

_See property access [examples.](#property-access-examples)_

## Relationships
| Relationship | Type	|Description| Req. Set|
|:---------------|:--------|:----------|:----|
|worksheet|[Worksheet](worksheet.md)|Gets the worksheet that is added to the workbook.|[ApiSet.InProgressFeatures.Event](../requirement-sets/excel-api-requirement-sets.md)|

## Methods
None

