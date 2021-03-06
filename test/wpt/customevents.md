---
title: CustomEvents
description: CustomEvents
MSHAttr:
- 'PreferredSiteName:MSDN'
- 'PreferredLib:/library/windows/hardware'
ms.assetid: 733182b7-9588-45db-a3c0-5c2a5d48edbe
ms.mktglfcycl: operate
ms.sitesec: msdn
ms.author: sapaetsc
ms.date: 05/05/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-oem
---


# CustomEvents

Represents a collection of custom events.


## Element Hierarchy

* \<[WindowsPerformanceRecorder](windowsperformancerecorder.md)\>
  * \<[TraceMergeProperties](tracemergeproperties.md)\>
    * \<[TraceMergeProperty](tracemergeproperty.md)\>
      * \<**CustomEvents**\>


## Syntax

```
<CustomEvents Operation = "Set" | "Add"

  <!-- Child elements -->
  CustomEvent

</CustomEvents>
```


## Attributes and Elements


### Attributes

<table>
<thead>
<tr class="header">
<th>Attribute</th>
<th>Description</th>
<th>Data type</th>
<th>Required</th>
<th>Default</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Operation</strong></p></td>
<td><p>Indicates whether custom events should be set or added.</p></td>
<td><p>This attribute can have one of the following values:</p>
<ul>
<li><p>Set</p></li>
<li><p>Add</p></li>
<li><p>Remove</p></li>
</ul></td>
<td><p>No</p></td>
<td><p>Set</p></td>
</tr>
</tbody>
</table>


### Child Elements

| Element                       | Description                | Requirement            |
|:------------------------------|:---------------------------|:-----------------------|
| [CustomEvent](customevent.md) | Represents a custom event. | Required, one or more. |


### Parent Elements

| Element                                     | Description                                                                                                  |
|:--------------------------------------------|:-------------------------------------------------------------------------------------------------------------|
| [TraceMergeProperty](tracemergeproperty.md) | Contains configurations that are applied when event trace log (ETL) files from multiple profiles are merged. |


## Example

The following code example shows how this element is used.

```
<TraceMergeProperty
  Id="TraceMerge_Default"
  Name="TraceMerge_Default">
  <DeletePreMergedTraceFiles
    Value="true"/>
  <CustomEvents>
    <CustomEvent
      Value="ImageId"/>
    <CustomEvent
      Value="BuildInfo"/>
    <CustomEvent
      Value="VolumeMapping"/>
    <CustomEvent
      Value="EventMetadata"/>
    <CustomEvent
      Value="PerfTrackMetadata"/>
    <CustomEvent
      Value="WinSAT"/>
    <CustomEvent
      Value="NetworkInterface"/>
  </CustomEvents>
</TraceMergeProperty>
```


## Related topics

[Elements](elements.md)

