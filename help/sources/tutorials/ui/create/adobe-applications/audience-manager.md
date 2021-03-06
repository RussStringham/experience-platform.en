---
keywords: Experience Platform;home;popular topics;Audience manager source connector;Audience Manager;audience manager connector
solution: Experience Platform
title: Create an Adobe Audience Manager source connector in the UI
topic: overview
type: Tutorial
description: This tutorial walks you through the steps to create a source connectors for Adobe Audience Manager to bring in Consumer Experience Event data into Platform using the user interface.
---

# Create an Adobe Audience Manager source connector in the UI

This tutorial walks you through the steps to create a source connector for Adobe Audience Manager to bring in Consumer Experience Event data into Platform using the user interface.

## Create a source connection with Adobe Audience Manager

Log in to [Adobe Experience Platform](https://platform.adobe.com) and then select **[!UICONTROL Sources]** from the left navigation bar to access the [!UICONTROL Sources] workspace. The [!UICONTROL Catalog] screen displays a variety of sources for which you can create an account with.

Under the [!UICONTROL Adobe applications] category, select **[!UICONTROL Adobe Audience Manager]** and then select **[!UICONTROL Configure]**.

![catalog](../../../../images/tutorials/create/aam/catalog.png)

The [!UICONTROL Select traits and segments] step appears, providing you with an interactive interface to explore and select your traits, segments, and data.

* The left panel of the interface contains the [!UICONTROL Select traits and segments] options, as well as a hierarchical directory of all segments available to you.
* The right half of the interface allows you to interact with selected segments and pick through specific data you want to use.

![add-data](../../../../images/tutorials/create/aam/add-data.png)

To navigate through available segments, select the folder you want to access from the [!UICONTROL All Segments] panel. Selecting a folder allows you to traverse a folder's hierarchy and provides you with a list of segments to filter through.

![segment-folder](../../../../images/tutorials/create/aam/segment-folder.png)

Once you have identified and selected the segments you want to use, a new panel appears on the right, displaying your list of selected items. You can continue to access different folders and select different segments for your connection. Selecting more segments updates the panel on the right.

![select-data](../../../../images/tutorials/create/aam/select-data.png)

Alternatively, you can select the **[!UICONTROL Select all segments]** and **[!UICONTROL Select all traits]** boxes. Selecting all segments will bring Audience Manager segments to Platform, while selecting all traits enables all first party traits from Audience Manager.

Once you are finished, select **[!UICONTROL Next]**

![all-segments](../../../../images/tutorials/create/aam/all-segments.png)

The [!UICONTROL Review] step appears, allowing you to review your selected traits and segments before they are connected to Platform. Details are grouped within the following categories:

* **[!UICONTROL Connection]**: Shows the source platform and the status of the connection.
* **[!UICONTROL Selected data]**: Shows the number of selected segments and enabled traits.

![review](../../../../images/tutorials/create/aam/review.png)

Once you have reviewed your dataflow, select **[!UICONTROL Finish]** and allow some time for the dataflow to be created.

## Next steps

While an Audience Manager dataflow is active, incoming data is automatically ingested into Real-time Customer Profiles. You can now utilize this incoming data and create audience segments using Platform Segmentation Service. See the following documents for more details:

* [Real-time Customer Profile overview](../../../../../profile/home.md)
* [Segmentation Service overview](../../../../../segmentation/home.md)