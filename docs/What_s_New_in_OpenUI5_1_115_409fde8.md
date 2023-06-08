<!-- loio409fde8b73364f5bb49905a669a57503 -->

| loio |
| -----|
| 409fde8b73364f5bb49905a669a57503 |

<div id="loio">

view on: [demo kit nightly build](https://sdk.openui5.org/nightly/#/topic/409fde8b73364f5bb49905a669a57503) | [demo kit latest release](https://sdk.openui5.org/topic/409fde8b73364f5bb49905a669a57503)</div>

<link rel="stylesheet" type="text/css" href="css/sap-icons.css"/>

## What's New in OpenUI5 1.115

With this release OpenUI5 is upgraded from version 1.114 to 1.115.

> ### Note:  
> Content marked as <span style="color:#666666;"><span class="SAP-icons"></span></span>** [Preview](https://help.sap.com/docs/whats-new-disclaimer)** is provided as a courtesy, without a warranty, and may be subject to change. For more information, see the [preview disclaimer](https://help.sap.com/docs/whats-new-disclaimer).

** **


<table>
<tr>
<th valign="top">

Version



</th>
<th valign="top">

Type



</th>
<th valign="top">

Category



</th>
<th valign="top">

Title



</th>
<th valign="top">

Description



</th>
<th valign="top">

Action



</th>
<th valign="top">

Available as of



</th>
</tr>
<tr>
<td valign="top">

 Upcoming 



</td>
<td valign="top">

 Deleted 



</td>
<td valign="top">

 Announcement 



</td>
<td valign="top">

 **End of Cloud Provisioning for OpenUI5 Versions \(Q2/2023\)** 



</td>
<td valign="top">

**End of Cloud Provisioning for OpenUI5 Versions \(Q2/2023\)**

The following OpenUI5 versions will be removed from the OpenUI5 Content Delivery Network \(CDN\) after the end of Q2/2023.

**Minor Versions Reaching Their End of Cloud Provisioning**

The following versions including all patches will be removed entirely:

-   1.91
-   1.99
-   1.100
-   1.101

**Action**: Upgrade to a version that’s still in maintenance.

**Patch Versions Reaching Their End of Cloud Provisioning**

The following patches will be removed:

-   Long-term maintenance versions:

    -   1.38.54
    -   1.71.2
    -   1.71.44-1.71.45
    -   1.84.23 to 1.84.24
    -   1.96.7 to 1.96.8

    **Action**: Upgrade to the latest available patch for the respective OpenUI5 version.

-   Other versions

    -   1.102.0 to 1.102.1

    **Action**: Upgrade to a version that’s still in maintenance.


For more information, see [UI5 Releases Ending Service in 2023](https://blogs.sap.com/2022/12/05/ui5-releases-ending-service-in-2023/) and [Version Overview](https://sdk.openui5.org/versionoverview.html).

<sub><span style="color:#666666;"><span class="SAP-icons"></span></span>** [Preview](https://help.sap.com/docs/whats-new-disclaimer)**•Deleted•Announcement•Required•Upcoming</sub>



</td>
<td valign="top">

 Required 



</td>
<td valign="top">

2023-06-30



</td>
</tr>
<tr>
<td valign="top">

 Upcoming 



</td>
<td valign="top">

 Deprecated 



</td>
<td valign="top">

 Announcement 



</td>
<td valign="top">

 **`sap.ui.table` Controls: Discontinued Use of `sap.ui.commons` Library** 



</td>
<td valign="top">

**`sap.ui.table` Controls: Discontinued Use of `sap.ui.commons` Library**

We will discontinue the use of the deprecated `sap.ui.commons` library as of OpenUI5 version 1.118. If you use shortcuts for defining titles, footers, column headers, and cell templates in your `sap.ui.table` controls based on the related controls in the `sap.ui.commons` library, these will no longer work. Instead, the `sap.ui.table` controls will always depend on the related controls in the `sap.m` library after version 1.118.

**Recommended Action**: Check which libraries are used in your application. If you use `sap.ui.table` controls and their shortcuts in combination with the `sap.ui.commons` library, make sure to switch to the `sap.m` library.

For more information about how to prepare for this change, see [Change to the SAPUI5 sap.ui.table library](https://blogs.sap.com/2023/05/25/change-to-the-sapui5-sap.ui.table-library/).

<sub><span style="color:#666666;"><span class="SAP-icons"></span></span>** [Preview](https://help.sap.com/docs/whats-new-disclaimer)**•Deprecated•Announcement•Recommended•Upcoming</sub>



</td>
<td valign="top">

 Recommended 



</td>
<td valign="top">

2023-09-07



</td>
</tr>
<tr>
<td valign="top">

 Upcoming 



</td>
<td valign="top">

 Changed 



</td>
<td valign="top">

 Announcement 



</td>
<td valign="top">

 **Planned Modern ECMAScript Support in OpenUI5** 



</td>
<td valign="top">

**Planned Modern ECMAScript Support in OpenUI5**

With OpenUI5 1.116, we intend to enable UI5 framework libraries to use modern ECMAScript syntax in their code and define Specification Version 3.0 in their UI5 Tooling configuration.

**Action:** If you use UI5 Tooling in your projects, upgrade to UI5 Tooling 3.0 and make sure that your project's development infrastructure fully supports this change.

For more information, see [Upgrade Your Tools for Modern ECMAScript in UI5](https://blogs.sap.com/2023/05/24/upgrade-your-tools-for-modern-ecmascript-in-ui5/).

<sub><span style="color:#666666;"><span class="SAP-icons"></span></span>** [Preview](https://help.sap.com/docs/whats-new-disclaimer)**•Changed•Announcement•Required•Upcoming</sub>



</td>
<td valign="top">

 Required 



</td>
<td valign="top">

2023-07-13



</td>
</tr>
<tr>
<td valign="top">

 1.115 



</td>
<td valign="top">

 Changed 



</td>
<td valign="top">

 Feature 



</td>
<td valign="top">

 **`sap.m.p13n.Engine`** 



</td>
<td valign="top">

**`sap.m.p13n.Engine`**

We have added more samples for the `Engine` and deprecated the following entities: `TablePersoController` and `TablePersoDialog`. For more information, see [Personalization](Personalization_75c08fd.md), the  [API Reference](https://sdk.openui5.org/api/sap.m.p13n.Engine), and the [Sample](https://sdk.openui5.org/entity/sap.m.p13n.Engine/sample/sap.m.sample.p13n.EngineGridTable) for `sap.ui.table.Table`, the [Sample](https://sdk.openui5.org/entity/sap.m.p13n.Engine/sample/sap.m.sample.p13n.Engine) for `sap.m.Table`, and the [Sample](https://sdk.openui5.org/entity/sap.m.p13n.Engine/sample/sap.m.sample.p13n.EngineGridList) for `sap.f.GridList`.

<sub>Changed•Feature•Info Only•1.115</sub>



</td>
<td valign="top">

 Info Only 



</td>
<td valign="top">

2023-06-15



</td>
</tr>
<tr>
<td valign="top">

 1.115 



</td>
<td valign="top">

 Deprecated 



</td>
<td valign="top">

 Control 



</td>
<td valign="top">

 ** `sap.ui.table.AnalyticalTable`, `sap.ui.table.Table`, `sap.ui.table.TreeTable`** 



</td>
<td valign="top">

**`sap.ui.table.AnalyticalTable`, `sap.ui.table.Table`, `sap.ui.table.TreeTable`**

We have deprecated the `editable` property. For more information, see the [API Reference](https://sdk.openui5.org/api/sap.ui.table.Table).

<sub>Deprecated•Control•Info Only•1.115</sub>



</td>
<td valign="top">

 Info Only 



</td>
<td valign="top">

2023-06-15



</td>
</tr>
<tr>
<td valign="top">

 1.115 



</td>
<td valign="top">

 New 



</td>
<td valign="top">

 Feature 



</td>
<td valign="top">

 **Introduction of `sap.ui.mdc` library \(experimental\)** 



</td>
<td valign="top">

**Introduction of `sap.ui.mdc` library \(experimental\)**

We have introduced the `sap.ui.mdc` library experimentally. This library contains smart composite controls that are metadata-driven and allow applications to use them with any OpenUI5 model and any data protocol. For more information, see [sap.ui.mdc \(experimental\)](sap_ui_mdc_experimental_1dd2aa9.md) and the  [API Reference](https://sdk.openui5.org/api/sap.ui.mdc).

<sub>New•Feature•Info Only•1.115</sub>



</td>
<td valign="top">

 Info Only 



</td>
<td valign="top">

2023-06-15



</td>
</tr>
<tr>
<td valign="top">

 1.115 



</td>
<td valign="top">

 Changed 



</td>
<td valign="top">

 Feature 



</td>
<td valign="top">

 **OpenUI5 OData V4 Model** 



</td>
<td valign="top">

**OpenUI5 OData V4 Model**

The new version of the OpenUI5 OData V4 model introduces the following features:

-   You can now close the current changeset in `Auto` groups by calling `sap.ui.model.odata.v4.ODataModel#submitBatch`. For any additional change requests that are created afterwards and make it into the same `$batch` request, a new changeset is created.

    For more information, see the [API Reference](https://sdk.openui5.org/api/sap.ui.model.odata.v4.ODataModel/methods/submitBatch).

-   We now support the "Deep Create" scenario for navigation properties of cardinality "many", that is, collection-valued navigation properties.

    For more information, see [Creating an Entity](Creating_an_Entity_c9723f8.md).


<sub>Changed•Feature•Info Only•1.115</sub>



</td>
<td valign="top">

 Info Only 



</td>
<td valign="top">

2023-06-15



</td>
</tr>
<tr>
<td valign="top">

 1.115 



</td>
<td valign="top">

 Changed 



</td>
<td valign="top">

 Feature 



</td>
<td valign="top">

 **OpenUI5 OData Types** 



</td>
<td valign="top">

**OpenUI5 OData Types**

The new version of OpenUI5 provides the `parseEmptyValueToZero` format option for the following numeric OData types:

-   `sap.ui.model.odata.type.Byte`
-   `sap.ui.model.odata.type.Decimal`
-   `sap.ui.model.odata.type.Double`
-   `sap.ui.model.odata.type.Int`
-   `sap.ui.model.odata.type.Int16`
-   `sap.ui.model.odata.type.Int32`
-   `sap.ui.model.odata.type.Int64`
-   `sap.ui.model.odata.type.SByte`
-   `sap.ui.model.odata.type.Single`

Empty input, that is, `null` or `""`, is parsed to 0 if `parseEmptyValueToZero` is set to `true` and if the `nullable` constraint is `false`.

For more information, see, for example, the [API Reference](https://sdk.openui5.org/api/sap.ui.model.odata.type.Int16) for `sap.ui.model.odata.type.Int16`.

<sub>Changed•Feature•Info Only•1.115</sub>



</td>
<td valign="top">

 Info Only 



</td>
<td valign="top">

2023-06-15



</td>
</tr>
<tr>
<td valign="top">

 1.115 



</td>
<td valign="top">

 Changed 



</td>
<td valign="top">

 Control 



</td>
<td valign="top">

 **`sap.ui.integration.widgets.Card`** 



</td>
<td valign="top">

**`sap.ui.integration.widgets.Card`**

-   Using the new \(experimental\) `modelSizeLimit` property, you can set the maximum number of entries that are used for all list bindings inside the card. This feature is important for cards that use forms and filters. The default `modelSizeLimit` value is 1000. For more information, see the [Integration Card Configuration](https://sdk.openui5.org/test-resources/sap/ui/integration/demokit/cardExplorer/webapp/index.html#/learn/configuration) section and the [Sample](https://sdk.openui5.org/test-resources/sap/ui/integration/demokit/cardExplorer/webapp/index.html#/explore/data/modelSizeLimit) in the Card Explorer.

-   We have \(experimentally\) introduced a new input field in the Object Card that enables the users to pick a date.

    For more information, see the [Object Card](https://sdk.openui5.org/test-resources/sap/ui/integration/demokit/cardExplorer/webapp/index.html#/learn/typesDeclarative/object) section and the [Sample](https://sdk.openui5.org/test-resources/sap/ui/integration/demokit/cardExplorer/webapp/index.html#/explore/object/form) in the Card Explorer.

-   We have introduced a new `showColon` property for labels in the Object Card. When set to `false` it hides the colons. The default value is `true`, in which case all colons are automatically shown. For more information, see the [Object Card](https://sdk.openui5.org/test-resources/sap/ui/integration/demokit/cardExplorer/webapp/index.html#/learn/typesDeclarative/object) section and the [Sample](https://sdk.openui5.org/test-resources/sap/ui/integration/demokit/cardExplorer/webapp/index.html#/explore/object/form) in the Card Explorer.


<sub>Changed•Control•Info Only•1.115</sub>



</td>
<td valign="top">

 Info Only 



</td>
<td valign="top">

2023-06-15



</td>
</tr>
<tr>
<td valign="top">

 1.115 



</td>
<td valign="top">

 Changed 



</td>
<td valign="top">

 Control 



</td>
<td valign="top">

 **sap.m.Button** 



</td>
<td valign="top">

**sap.m.Button**

We have added a new `accessibleRole` property that can receive a value from an enumeration called `sap.m.ButtonAccessibleRole` and the application developer can select one of two values – `Default` or `Link`.

 For more information, see the [API Reference](https://sdk.openui5.org/api/sap.m.ButtonAccessibleRole). 

<sub>Changed•Control•Info Only•1.115</sub>



</td>
<td valign="top">

 Info Only 



</td>
<td valign="top">

2023-06-15



</td>
</tr>
<tr>
<td valign="top">

 1.115 



</td>
<td valign="top">

 Changed 



</td>
<td valign="top">

 Control 



</td>
<td valign="top">

 **sap.m.DynamicDateRange** 



</td>
<td valign="top">

**sap.m.DynamicDateRange**

We removed the experimental tag of the control. This changes the API to make the control more stable and easier to use.

 For more information, see the [API Reference](https://sdk.openui5.org/api/sap.m.DynamicDateRange). 

<sub>Changed•Control•Info Only•1.115</sub>



</td>
<td valign="top">

 Info Only 



</td>
<td valign="top">

2023-06-15



</td>
</tr>
<tr>
<td valign="top">

 1.115 



</td>
<td valign="top">

 Changed 



</td>
<td valign="top">

 Control 



</td>
<td valign="top">

 **sap.m.Wizard** 



</td>
<td valign="top">

**sap.m.Wizard**

We have provided an API that will allow the application to change the H level based on your needs so that the correct heading level structure is presented on the page. For more information, see the [API Reference](https://sdk.openui5.org/api/sap.m.Wizard). 

<sub>Changed•Control•Info Only•1.115</sub>



</td>
<td valign="top">

 Info Only 



</td>
<td valign="top">

2023-06-15



</td>
</tr>
<tr>
<td valign="top">

 1.115 



</td>
<td valign="top">

 Changed 



</td>
<td valign="top">

 Control 



</td>
<td valign="top">

 **sap.f.SidePanel** 



</td>
<td valign="top">

**sap.f.SidePanel**

We have added the ability to place the `sap.f.SidePanel` control on the left side of the screen. Previously it was fixed only to the right side.

 For more information, see the [API Reference](https://sdk.openui5.org/api/sap.f.SidePanel). 

<sub>Changed•Control•Info Only•1.115</sub>



</td>
<td valign="top">

 Info Only 



</td>
<td valign="top">

2023-06-15



</td>
</tr>
</table>

